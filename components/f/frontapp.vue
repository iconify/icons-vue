<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":366};
const content = `<defs><linearGradient id="SVGR2kvIebn" x1="12.519%" x2="88.228%" y1="85.213%" y2="10.023%"><stop offset="0%" class="a5ysrvcjf"/><stop offset="86.135%" class="fmxqzo-2j"/></linearGradient></defs><path class="ey52gqkoe"/><circle fill="url(#SVGR2kvIebn)" transform="rotate(90 147.013 147.015)" class="qy6e0wbcr"/><circle fill="url(#SVGR2kvIebn)" transform="rotate(90 147.013 147.015)" class="pylmo0b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:frontapp" /></template>
<style>
.a5ysrvcjf {
  stop-color: var(--svg-color--ff0057, #ff0057);
  stop-opacity: 0.16;
}

.ey52gqkoe {
  fill: var(--svg-color--001b38, #001b38);
  d: path("M0 60.854C0 27.245 27.245 0 60.854 0h195.143v86.6c0 16.804-13.623 30.427-30.427 30.427h-79.762c-15.805.25-28.565 13.033-28.781 28.846v189.41c0 16.804-13.622 30.427-30.427 30.427H0z");
}

.fmxqzo-2j {
  stop-color: var(--svg-color--ff0057, #ff0057);
}

.pylmo0b-w {
  cx: 147.013px;
  cy: 147.015px;
  r: 78.993px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qy6e0wbcr {
  cx: 147.013px;
  cy: 147.015px;
  r: 78.993px;
}

</style>
