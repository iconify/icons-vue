<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mlq_w7beu"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fine-ticket-sharp" /></template>
<style>
.mlq_w7beu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.75v-2h12.5V10h-2v4h2v7.25H5.75V14h2v-4h-2ZM12 7v5.5");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
