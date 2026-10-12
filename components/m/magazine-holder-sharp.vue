<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="aeeh76pet"/><path class="y83m_hi6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magazine-holder-sharp" /></template>
<style>
.aeeh76pet {
  d: path("M4.75 19.75v-8l1.06-1.06l6.88-6.88l1.06-1.06h5.5v18.5H4.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y83m_hi6j {
  d: path("M8.25 14.25h7.5v4h-7.5z");
}

</style>
