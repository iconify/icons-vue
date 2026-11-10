<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="h4_iwpbgh"/><path class="v65b3130e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-bullet-indent-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h4_iwpbgh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 5C5 5.83 4.328 6.5 3.5 6.5C2.672 6.5 2 5.83 2 5C2 4.17 2.672 3.5 3.5 3.5C4.328 3.5 5 4.17 5 5ZM7 12C7 12.83 6.328 13.5 5.5 13.5C4.672 13.5 4 12.83 4 12C4 11.17 4.672 10.5 5.5 10.5C6.328 10.5 7 11.17 7 12ZM9 19C9 19.83 8.328 20.5 7.5 20.5C6.672 20.5 6 19.83 6 19C6 18.17 6.672 17.5 7.5 17.5C8.328 17.5 9 18.17 9 19Z");
  stroke: none;
}

.v65b3130e {
  d: path("M11 19H22M9 12H20M7 5H18");
}

</style>
