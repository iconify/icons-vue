<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xp15q7bgg"/><path class="mrg47gb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:armoury-crate" /></template>
<style>
.mrg47gb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 26.925l-5.85 9.75l5.85-1.95l5.85 1.95Z");
}

.xp15q7bgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.425L4.5 40.575l9.75-3.9L24 19.125l9.75 17.55l9.75 3.9Z");
}

</style>
