<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o843w809a"/><path class="uifpeac6e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-hand" /></template>
<style>
.o843w809a {
  d: path("M2.5 13.5H5c1.5 0 3 .75 4 1.75h3.5a1.25 1.25 0 0 1 0 2.5H9.25");
}

.uifpeac6e {
  d: path("M2.5 20.5h9c1 0 1.75-.25 2.5-.75l5.75-4.25a1.5 1.5 0 0 0-2-2.25l-4 2.75m-2.25-5S7 8.25 7 5.5C7 4.05 8.05 3 9.5 3c.75 0 1.55.5 2 1.25c.45-.75 1.25-1.25 2-1.25C14.95 3 16 4.05 16 5.5c0 2.75-4.5 5.5-4.5 5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
