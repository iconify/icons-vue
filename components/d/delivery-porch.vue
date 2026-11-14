<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h9asee4qz"/><path class="d0khbjb2l"/><path class="m86rgxj-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-porch" /></template>
<style>
.d0khbjb2l {
  d: path("M7 10.5h1.25a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5H7A1.5 1.5 0 0 1 5.5 16v-4A1.5 1.5 0 0 1 7 10.5m-2 7h14a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 19A1.5 1.5 0 0 1 5 17.5m11.786-7.016l1.75 1.077a1.5 1.5 0 0 1 .714 1.277v1.824a1.5 1.5 0 0 1-.714 1.277l-1.75 1.077a1.5 1.5 0 0 1-1.572 0l-1.75-1.077a1.5 1.5 0 0 1-.714-1.277v-1.824a1.5 1.5 0 0 1 .714-1.277l1.75-1.077a1.5 1.5 0 0 1 1.572 0");
}

.h9asee4qz {
  d: path("M3.605 8.715L10.48 3.83a2.625 2.625 0 0 1 3.04 0l6.875 4.885a2.63 2.63 0 0 1 1.105 2.14v4.02a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 14.875v-4.02a2.63 2.63 0 0 1 1.105-2.14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m86rgxj-i {
  d: path("M12.75 12L16 14l3.25-2M16 14v3.5");
}

</style>
