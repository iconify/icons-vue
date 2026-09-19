<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vaios3b8m"/><path class="amiffdbug"/><circle class="l6cd208_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-with-monocle" /></template>
<style>
.amiffdbug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.8 19.825a7.578 7.578 0 1 0 15.155.007v-.007a7.578 7.578 0 1 0-15.155 0");
}

.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vaios3b8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.227 30.666c1.906-.536 9.543.43 11.297 1.66m-16.543-18.51a5.07 5.07 0 0 1 3.535-.862a5.07 5.07 0 0 1 3.377 1.398m14.599 2.665c-1.942-1.387-4.304 0-6.622-.21m-8.696 3.171a2.414 2.414 0 0 1-4.826 0c0-1.331 1.081-2.413 2.413-2.413s2.413 1.082 2.413 2.413m13.674 1.609a2.414 2.414 0 0 1-4.826 0c0-1.331 1.081-2.413 2.413-2.413s2.413 1.082 2.413 2.413m5.379-1.643s1.78.443 1.547 3.227c-.232 2.785-2.87 6.405-2.87 6.405s-1.626 1.9-1.175 3.476c.576 2.016 3.47 5.177 3.362 6.925");
}

</style>
