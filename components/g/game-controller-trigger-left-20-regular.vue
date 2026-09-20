<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l-h-5js6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-trigger-left-20-regular" /></template>
<style>
.l-h-5js6i {
  fill: currentColor;
  d: path("M14.36 2c1.497 0 2.967.817 3.274 2.438C17.84 5.529 18 7.03 18 9c0 2.62-.92 4.88-2.592 6.485C13.738 17.09 11.358 18 8.5 18c-.929 0-2.877.088-4.237-.197a1.6 1.6 0 0 1-.86-.461a1.56 1.56 0 0 1-.395-.805c-.103-.568.056-1.197.344-1.73C4.123 13.38 5 11.506 5 9.5c0-1.557-.251-3.237-1.169-5.26C3.38 3.244 4.054 2 5.223 2zM5.222 3c-.366 0-.664.423-.48.826C5.724 5.993 6 7.816 6 9.5c0 2.272-.987 4.337-1.769 5.783c-.216.401-.289.797-.239 1.075a.56.56 0 0 0 .138.296a.62.62 0 0 0 .338.17C5.695 17.081 7.477 17 8.5 17c2.642 0 4.761-.839 6.216-2.235C16.169 13.369 17 11.379 17 9c0-1.916-.155-3.356-.349-4.377C16.461 3.616 15.536 3 14.36 3zM8.5 7a.5.5 0 0 1 .5.5V11h1.5a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 .5-.5m6 0a.5.5 0 0 1 0 1h-1v3.5a.5.5 0 0 1-1 0V8h-1a.5.5 0 0 1 0-1z");
}

</style>
