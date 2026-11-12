<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yo7b8frfe"/><path class="f-3d8rbtb"/><path class="s6es03xrf"/><path class="i7y13bc4y"/><rect class="fauwf6bhv"/><rect class="qsmbhrb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-scan-line-duotone" /></template>
<style>
.f-3d8rbtb {
  stroke-linecap: round;
  d: path("M12 18.4805L12 5.54094");
}

.fauwf6bhv {
  width: 0.928px;
  height: 12.98px;
  x: 8.285px;
  y: 5.52px;
  rx: 0.464px;
}

.i7y13bc4y {
  stroke-linecap: round;
  d: path("M14.7861 18.4805L14.7861 5.54094");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qsmbhrb9y {
  width: 0.928px;
  height: 12.98px;
  x: 17.572px;
  y: 5.5px;
  rx: 0.464px;
}

.s6es03xrf {
  stroke-linecap: round;
  d: path("M5.5 18.4805L5.5 5.54094");
}

.yo7b8frfe {
  stroke-linecap: round;
  d: path("M22 14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
