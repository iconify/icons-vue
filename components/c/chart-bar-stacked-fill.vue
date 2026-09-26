<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-x5jbb0q"/><path class="yo50hku1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-bar-stacked-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-x5jbb0q {
  fill: currentColor;
  d: path("M8 4L15 4C16.1046 4 17 4.8954 17 6L17 8C17 9.1046 16.1046 10 15 10L8 10C6.8954 10 6 9.1046 6 8L6 6C6 4.8954 6.8954 4 8 4ZM8 12L18 12C19.1046 12 20 12.8954 20 14L20 16C20 17.1046 19.1046 18 18 18L8 18C6.8954 18 6 17.1046 6 16L6 14C6 12.8954 6.8954 12 8 12ZM13 6L13 8L15 8L15 6L13 6ZM15 14L15 16L18 16L18 14L15 14Z");
  stroke: none;
}

.yo50hku1m {
  d: path("M3 3L3 19C3 20.1046 3.8954 21 5 21L21 21");
}

</style>
