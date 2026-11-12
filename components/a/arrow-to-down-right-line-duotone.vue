<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mbxu6qbgd"/><path class="jczlw7b5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-down-right-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jczlw7b5o {
  d: path("M12 19.5L12 9.5C12 7.83333 13 4.5 17 4.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mbxu6qbgd {
  stroke-linejoin: round;
  d: path("M7 14.5L12 19.5L17 14.5");
}

</style>
