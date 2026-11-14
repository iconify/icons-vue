<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h5671682r"/><path class="wp-am0bed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:do-not-disturb-home" /></template>
<style>
.h5671682r {
  d: path("M11.544 20.5H3.5v-10L12 3.25l8.5 7.25v1.356");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wp-am0bed {
  d: path("M18.75 14.25a3.75 3.75 0 1 0 2.25 5a3 3 0 0 1-2.25-5Z");
}

</style>
