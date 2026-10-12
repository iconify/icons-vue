<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jd-3p_okg"/><path class="mgf3jubms"/><path class="n6kpvbb3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:captain-hat-sharp" /></template>
<style>
.jd-3p_okg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.75C3 7.25 7 5 12 5s9 2.25 9 4.75v1.8l-2.25.45v2.5H5.25V12L3 11.55zM5.25 12h13.5");
}

.mgf3jubms {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.25h.01");
}

.n6kpvbb3a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 17.5h13.5l-.6 1.6l-.576 1.4H6.626l-.576-1.4Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
