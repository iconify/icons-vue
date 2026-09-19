<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="umwwsxbhh"/><rect class="aot376n3t"/><path class="xaezclbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitmoji" /></template>
<style>
.aot376n3t {
  width: 4.98px;
  height: 6.33px;
  x: 26.35px;
  y: 12.59px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.49px;
}

.umwwsxbhh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.59 5.5H12.41a4.57 4.57 0 0 0-4.56 4.57v21.25a4.58 4.58 0 0 0 4.56 4.57h10v6.61L29 35.89h6.56a4.58 4.58 0 0 0 4.56-4.57V10.07a4.57 4.57 0 0 0-4.53-4.57");
}

.xaezclbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.16 13.26a2.51 2.51 0 0 0-2.49 2.5v.67c0 1.37 1.12-.24 2.49-.24h0c1.37 0 2.49 1.61 2.49.24v-.67a2.51 2.51 0 0 0-2.49-2.5m-3.75 8.95a8.59 8.59 0 1 0 17.18 0Z");
}

</style>
