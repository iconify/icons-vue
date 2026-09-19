<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="urlsyf_bb"/><path class="wml-7lc8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freereels" /></template>
<style>
.urlsyf_bb {
  width: 21.748px;
  height: 33.645px;
  x: 13.156px;
  y: 6.847px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.877px;
  ry: 5.877px;
}

.wml-7lc8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.466 10.853l-3.524.563c-2.851.453-4.807 3.15-4.343 6l2.542 16a5.22 5.22 0 0 0 5.944 4.353m20.51-26.916l3.525.563c2.851.453 4.807 3.15 4.343 6l-2.542 16a5.22 5.22 0 0 1-5.944 4.353M28.743 22.58l-6.84-4.148a1.08 1.08 0 0 0-1.64.924v8.294c0 .842.92 1.36 1.64.924l6.84-4.147a1.08 1.08 0 0 0 0-1.848Z");
}

</style>
