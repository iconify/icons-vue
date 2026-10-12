<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="leq-9tb_y"/><path class="fkjn2jbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:corrosive-sharp" /></template>
<style>
.fkjn2jbsb {
  d: path("m10 7.5l1.5 1.875v.875a1.5 1.5 0 0 1-3 0v-.875zM14 9l1.5 1.875v.875a1.5 1.5 0 0 1-3 0v-.875zm-6 7h2.75L12 17.25L13.25 16H16");
}

.leq-9tb_y {
  d: path("m13.59 3.84l6.57 6.57L21.75 12l-1.59 1.59l-6.57 6.57L12 21.75l-1.59-1.59l-6.57-6.57L2.25 12l1.59-1.59l6.57-6.57L12 2.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
