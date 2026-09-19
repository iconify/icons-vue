<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xopy01blk"/><path class="xz80ok1hp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bima" /></template>
<style>
.xopy01blk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 28.073s-1.894-3.694-7.293-4.452L33.745 7.804L24 8.941l-9.745-1.137l-2.462 15.817C6.394 24.38 4.5 28.073 4.5 28.073zm-31.623 0c0 6.695 5.428 12.123 12.123 12.123s12.123-5.428 12.123-12.123");
}

.xz80ok1hp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.833 32.05a4.167 4.167 0 0 0 8.334 0z");
}

</style>
