<script>
    export let icon;
    export let link;
  
    function handleClick() {
      window.location.href = link;
    }
  </script>
  
  <main>
    <div on:click={handleClick} class="icon">{icon}</div>
  </main>
  
  <style>
    .icon {
      cursor: pointer;
    }
  </style>
  
  
    