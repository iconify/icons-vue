<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gwpkjccoj"/><path class="ptzg8vaxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:intra" /></template>
<style>
.gwpkjccoj {
  cx: 24px;
  cy: 19.218px;
  r: 10.561px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ptzg8vaxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 39.343l19.5-19.5l19.5 19.5z");
}

</style>
