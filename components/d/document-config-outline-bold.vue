<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="f9z-0cczq"/><path class="vmk3-8b7s"/><path class="wluwrgbwr"/><path class="xaqt94wpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:document-config-outline-bold" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.f9z-0cczq {
  d: path("M9 10.5h6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vmk3-8b7s {
  d: path("M13.5 8.5v4");
}

.wluwrgbwr {
  d: path("M9 14.5h6");
}

.xaqt94wpa {
  d: path("M10.5 12.5v4");
}

</style>
