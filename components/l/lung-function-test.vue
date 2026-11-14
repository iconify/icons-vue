<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p75rnpb5j"/><path class="ebabboxfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lung-function-test" /></template>
<style>
.ebabboxfi {
  d: path("m8 8.75l1.75-2l1.75 2M15 21.5v-3m3 3V15m3 6.5V17");
}

.p75rnpb5j {
  d: path("M8 6.5c-1.75-2-4.5.25-4.5 4.5c0 2.5.5 4 1.75 4C7 15 8 14.25 8 12.75Zm7.202 7.868c-.318.412-.723.632-1.202.632c-1.5 0-2.75-.75-2.75-2.25V6.5c2-2 4.75.25 4.75 4.5q0 .635-.063 1.18M9.75 2.5v4.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
