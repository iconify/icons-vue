<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gzjgc_t0q"/><path class="ayaekoj_p"/><path class="alu6i0_jj"/><path class="q5lasnb7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:book-line-duotone" /></template>
<style>
.alu6i0_jj {
  d: path("M8 7H16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ayaekoj_p {
  d: path("M19.8978 16H7.89778C6.96781 16 6.50282 16 6.12132 16.1022C5.08604 16.3796 4.2774 17.1883 4 18.2235");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.gzjgc_t0q {
  d: path("M10 22H14C16.8284 22 18.2426 22 19.1213 21.1213C20 20.2426 20 18.8284 20 16V8C20 5.17157 20 3.75736 19.1213 2.87868C18.2426 2 16.8284 2 14 2H10C7.17157 2 5.75736 2 4.87868 2.87868C4 3.75736 4 5.17157 4 8V16C4 18.8284 4 20.2426 4.87868 21.1213C5.75736 22 7.17157 22 10 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q5lasnb7b {
  d: path("M8 10.5H13");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
