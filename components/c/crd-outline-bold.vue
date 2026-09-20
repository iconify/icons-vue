<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="mfc7nxp-y"/><path class="zf4ugsben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:crd-outline-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.mfc7nxp-y {
  d: path("M9 7h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zf4ugsben {
  d: path("m12 11 3 3 -3 3 -3 -3Z");
}

</style>
