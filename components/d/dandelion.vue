<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="vtusa__cp"/><path class="f5vv66bcg"/><path class="giaychbap"/><path class="kkel_fb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dandelion" /></template>
<style>
.f5vv66bcg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.25V4m1.94 3.06l1.6-1.6M14.75 9H17m-3.06 1.94l1.6 1.6m-5.48-1.6l-1.6 1.6M9.25 9H7m3.06-1.94l-1.6-1.6");
}

.giaychbap {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h.01m4.23 1.76h.01M18 9h.01m-1.77 4.24h.01m-8.49 0h.01M6 9h.01m1.75-4.24h.01");
}

.kkel_fb1c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.75v10.5m0-2.5c-1.25-2.25-3-3-5-3c.25 2.25 2 3.5 5 3");
}

.vtusa__cp {
  cx: 12px;
  cy: 9px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
