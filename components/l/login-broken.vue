<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="smxwd1bfv"/><path class="l6-4u2bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:login-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l6-4u2bgq {
  stroke-linejoin: round;
  d: path("M4 12H14M11 15L14 12L11 9");
}

.smxwd1bfv {
  d: path("M12 4C16.4183 4 20 7.58172 20 12M18.2454 17C16.7793 18.8289 14.5264 20 12 20");
}

</style>
