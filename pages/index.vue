<template>
  <main>
    <h1>Task Board</h1>
    <p>Crate a list of tasks</p>

    <div class="create-new">
      <input 
        type="text" 
        v-model="newTask" 
        placeholder="Add a new task" 
        @keypress.enter="addTask" />
    </div>
  </main>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
