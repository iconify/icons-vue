<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e4v2ds9kl"/><path class="t5fvfskyh"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-recurring" /></template>
<style>
.e4v2ds9kl {
  d: path("M12.471 17.997q-.22.004-.471.003c-.75 0-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6s8 2.5 8 6q0 .823-.219 1.553");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.t5fvfskyh {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m7.25 10A2.75 2.75 0 1 1 18 15.75");
}

</style>
