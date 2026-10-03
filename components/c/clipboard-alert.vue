<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k21c_kbvp"/><path class="chh9m8bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-alert" /></template>
<style>
.chh9m8bfh {
  fill: currentColor;
  d: path("M13 18C13 18.5523 12.5523 19 12 19C11.4477 19 11 18.5523 11 18C11 17.4477 11.4477 17 12 17C12.5523 17 13 17.4477 13 18Z");
  stroke: none;
}

.k21c_kbvp {
  d: path("M7 4C5.3431 4 4 5.3431 4 7L4 19C4 20.6569 5.3431 22 7 22L17 22C18.6569 22 20 20.6569 20 19L20 7C20 5.3431 18.6569 4 17 4M7 4C7 2.8954 7.8954 2 9 2L15 2C16.1046 2 17 2.8954 17 4L17 5C17 6.1046 16.1046 7 15 7L9 7C7.8954 7 7 6.1046 7 5L7 4ZM12 12L12 14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
