<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jp2tdyszl"/><path class="io1fqiqgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dragon" /></template>
<style>
.io1fqiqgn {
  d: path("M13.25 4.75c2-2 5.25-2.5 8.25-2.25c-2.75.75-4.25 2-5 3.5m-4 2.25h.01");
}

.jp2tdyszl {
  d: path("M2.5 7.75L10 6c1.5-1.5 4.5-1.75 6.5 0c2 2 3 6 3.5 9l1.5 6.5H13l-.5-5L5 16l-1.25-1.5l6.25-3L2.5 10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
