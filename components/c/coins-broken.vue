<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cj6dj02_r"/><path class="p4tkdpb3b"/><path class="xyh-7yb5t"/><path class="trp0jez5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:coins-broken" /></template>
<style>
.cj6dj02_r {
  d: path("M16 9C16 12.866 12.866 16 9 16C5.134 16 2 12.866 2 9C2 5.134 5.134 2 9 2C12.866 2 16 5.134 16 9Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4tkdpb3b {
  d: path("M15.9365 8.06299C17.3109 8.24859 18.5441 8.82399 19.5337 9.66639");
}

.trp0jez5m {
  d: path("M9 6.5V11.5");
}

.xyh-7yb5t {
  d: path("M21.5002 12.4008C21.8605 13.3004 22.0384 14.2878 21.9925 15.3133C21.8304 18.9332 18.9326 21.831 15.3127 21.9931C11.6928 22.1552 8.5475 19.528 8.0625 15.9371");
}

</style>
