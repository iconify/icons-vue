<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="noqktabui"/><path class="q_m7_eb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:egg-hatching" /></template>
<style>
.noqktabui {
  d: path("M12 2.5c4.5 0 7 7.5 7 12c0 4.25-3.25 7-7 7s-7-2.75-7-7c0-4.5 2.5-12 7-12Z");
}

.q_m7_eb_j {
  d: path("M12 2.5L10.5 6L13 9.5L11.5 12l3.5 1.25l-3.5 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
