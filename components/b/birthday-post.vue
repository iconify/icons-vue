<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="aqmj_4big"/><path class="eb4anvbxa"/><path class="dcnzi9b5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birthday-post" /></template>
<style>
.aqmj_4big {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3px;
}

.dcnzi9b5t {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.25h.01");
}

.eb4anvbxa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17.25v-3.5a1.25 1.25 0 0 1 1.25-1.25h7.5A1.25 1.25 0 0 1 17 13.75v3.5Zm5-4.75V10");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
