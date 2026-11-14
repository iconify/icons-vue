<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zw5bdvb3z"/><path class="fn8qnfaaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-image-edit" /></template>
<style>
.fn8qnfaaz {
  d: path("m5.5 12l3.75-3.75L13 12m1.5 9.5v-2L20 14l2 2l-5.5 5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zw5bdvb3z {
  d: path("M15.1 15H2.5V3H16v11.1");
}

</style>
