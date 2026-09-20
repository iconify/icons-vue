<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="j8p3ujb4c"/><path class="dmx-x9boq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-json-outline-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.dmx-x9boq {
  d: path("M14 9.5a2.5 2.5 0 0 1 0 5");
}

.j8p3ujb4c {
  d: path("M10 14.5a2.5 2.5 0 0 1 0 -5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
