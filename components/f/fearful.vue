<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="dzf8fh4so"/><circle class="i2w7l1bsp"/><circle class="hv7t5-70z"/><circle class="usbadzy3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fearful" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.dzf8fh4so {
  d: path("M9.5 4.5v2M12 4.25v2m2.5-1.75v2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv7t5-70z {
  cx: 15px;
  cy: 10.5px;
  r: 1.25px;
}

.i2w7l1bsp {
  cx: 9px;
  cy: 10.5px;
  r: 1.25px;
}

.usbadzy3d {
  cx: 12px;
  cy: 16px;
  r: 1.75px;
}

</style>
