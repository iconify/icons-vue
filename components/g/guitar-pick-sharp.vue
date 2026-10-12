<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lz6exkb5s"/><path class="cun2tybbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:guitar-pick-sharp" /></template>
<style>
.cun2tybbm {
  d: path("m9 8.5l3 1.5l3-1.5");
}

.lz6exkb5s {
  d: path("M12 21.25c-1.25 0-7.1-8.15-7.95-11.9c-.9-4.1 2.95-6.6 7.95-6.6s8.85 2.5 7.95 6.6c-.85 3.75-6.7 11.9-7.95 11.9Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
