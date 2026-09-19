<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="bd-880z-u"/><circle class="om55k8b9c"/><path class="tqhifrbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gamesir-gamehub" /></template>
<style>
.bd-880z-u {
  cx: 27.25px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.om55k8b9c {
  cx: 32.75px;
  cy: 24px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tqhifrbbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.094 10.594L4.5 24l6.25 9.75h17m7.156 3.656L43.5 24l-6.25-9.75h-17m-4.45 7.281v4.938M18.269 24h-4.937");
}

</style>
