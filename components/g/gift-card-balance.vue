<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z6mabgozd"/><path class="xs45mxg8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-card-balance" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xs45mxg8r {
  d: path("M8.5 9.5c-2-4-4.25-3.75-3.75-1.5C5 9.25 7 9.5 8.5 9.5Zm0 0c2-4 4.25-3.75 3.75-1.5C12 9.25 10 9.5 8.5 9.5ZM20 16.25c-.25-.75-1-1.25-2-1.25c-1.1 0-1.75.6-1.75 1.5c0 1.75 3.75 1 3.75 3c0 .9-.75 1.5-2 1.5c-1 0-1.75-.5-2-1.25m2-6V15m0 6v1");
}

.z6mabgozd {
  d: path("M13.5 16H2V3h19.5v10.5M8.5 3v13M2 9.5h19.5");
}

</style>
