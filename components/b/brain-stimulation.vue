<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a6k2mj0wc"/><path class="qh_pjxbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brain-stimulation" /></template>
<style>
.a6k2mj0wc {
  d: path("M7.25 21.5V18c-2.25-1.5-3-3.5-3-5.75c0-3.75 2.75-6.5 6.5-6.5C14 5.75 16.5 8 16.5 11.5l1.5 3q0 .75-.75.75h-.75v2c0 1-.75 1.75-1.5 1.75h-1.75v2.5M12.75 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.qh_pjxbkl {
  d: path("M16.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0h2m-7.25 6.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
