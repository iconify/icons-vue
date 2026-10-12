<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="omicbmhtb"/><path class="vop2enb6d"/><circle class="gqdwd_bjh"/><path class="hjugcfd2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:budget-alert" /></template>
<style>
.gqdwd_bjh {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hjugcfd2j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.38 16.27c-.21-.45-.62-.75-1.12-.75c-.67 0-1.17.39-1.17.86c0 1.22 2.34.61 2.34 1.78c0 .49-.5.83-1.17.83c-.52 0-.96-.28-1.14-.73");
}

.omicbmhtb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 21.25h-5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h9a2.5 2.5 0 0 1 2.5 2.5v6m-10.5-4.5h7.5");
}

.vop2enb6d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 11.25h.01m3.24 0h.01m-3.26 3.5h.01M7.75 18h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
