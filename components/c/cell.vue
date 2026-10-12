<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="c-zwcbc_x"/><circle class="t635rwblu"/><path class="c1b2cxbio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cell" /></template>
<style>
.c-zwcbc_x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c5.5 0 9.25 3.6 9.25 8.6c0 5.6-4.3 9.9-9.5 9.9c-5.3 0-9-3.8-9-9.1c0-5.55 3.85-9.4 9.25-9.4");
}

.c1b2cxbio {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 14h.01M13 17h.01");
}

.t635rwblu {
  cx: 13.5px;
  cy: 10px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
