<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l86s6bcje"/><path class="kg6s3hb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allele-pair" /></template>
<style>
.kg6s3hb5i {
  d: path("M14.5 6a2 2 0 0 1 4 0v4.5l-1 1.5l1 1.5V18a2 2 0 0 1-4 0v-4.5l1-1.5l-1-1.5Z");
}

.l86s6bcje {
  fill: currentColor;
  d: path("M5.5 6a2 2 0 0 1 4 0v4.5l-1 1.5l1 1.5V18a2 2 0 0 1-4 0v-4.5l1-1.5l-1-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
