<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="g-ws7g5sh"/><path class="b9ih-fq0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flouci" /></template>
<style>
.b9ih-fq0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.134 25.909c2.39-2.26 7.04-1.292 6.975 5.554c-5.684-.064-9.107-1.42-6.975-5.554");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g-ws7g5sh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.807 3.038a5.1 5.1 0 0 1 .353 1.873c0 2.857-2.304 5.176-5.16 5.176s-5.16-2.32-5.16-5.176c0-.66.123-1.29.353-1.873M24 45.5s1.974-.99 4.04-3.767c-7.58 0-13.724-6.145-13.724-13.725S20.46 14.284 28.04 14.284s13.37 6.39 13.725 13.724c.236 4.873-.356 5.264-.356 5.264c2.067-2.907 3.94-6.713 3.94-6.713");
}

</style>
