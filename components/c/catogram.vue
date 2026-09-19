<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4u8l8s7k"/><circle class="f9sfqo6eu"/><path class="hx1iqlbub"/><path class="m032slbpk"/><circle class="qx-pikbva"/><path class="mgg1adh6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:catogram" /></template>
<style>
.f9sfqo6eu {
  cx: 17.19px;
  cy: 24.941px;
  r: 2.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hx1iqlbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 40.516h3.786c11.844 0 12.708-9.253 12.708-12.709V24.36c0-11.153-8.496-11.96-13.249-11.96h-6.49c-4.753 0-13.249.806-13.249 11.96v3.448c0 3.456.864 12.708 12.708 12.708Z");
}

.j4u8l8s7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.134 15.046c.586-2.158 2.762-7.561 4.382-7.561c1.944 0 4.104 4.914 4.104 4.914M4.662 24.819l4.896 1.638m-3.879 8.132l4.059-2.498M4.5 29.463h5.238");
}

.m032slbpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.866 15.046c-.586-2.158-2.762-7.561-4.382-7.561c-1.944 0-4.104 4.914-4.104 4.914m14.958 12.42l-4.896 1.638m3.879 8.132l-4.059-2.498m5.238-2.628h-5.238");
}

.mgg1adh6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.616 29.977l1.72-2.286a.77.77 0 0 0-.616-1.234h-3.44a.77.77 0 0 0-.616 1.234l1.72 2.286a.77.77 0 0 0 1.232 0");
}

.qx-pikbva {
  cx: 30.81px;
  cy: 24.941px;
  r: 2.093px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
