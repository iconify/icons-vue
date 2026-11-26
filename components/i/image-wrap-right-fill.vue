<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="o5_faqbcn"/><path class="qvon4o4uf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:image-wrap-right-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5_faqbcn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 6L19 6C20.6569 6 22 7.3431 22 9L22 15C22 16.6569 20.6569 18 19 18L13 18C11.3431 18 10 16.6569 10 15L10 9C10 7.3431 11.3431 6 13 6Z");
  stroke: none;
}

.qvon4o4uf {
  d: path("M3 3H21M3 21H21M3 9H7M3 15H7");
}

</style>
