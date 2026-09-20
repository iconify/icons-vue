<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="pkrewgbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:esewa" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pkrewgbrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.69 27.75a7.91 7.91 0 0 1-5.1 6.12a7.94 7.94 0 0 1-10.16-4.74l-1.76-4.84a7.94 7.94 0 0 1 4.74-10.16a7.94 7.94 0 0 1 10.16 4.74l.88 2.42l-14.9 5.42M45.5 24h-8");
}

</style>
