<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dqb8_vbxt"/><path class="we_b95bsc"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coming-soon" /></template>
<style>
.dqb8_vbxt {
  d: path("M7.5 2.5c2.25 1.75 3 4.25 3 7V13h-6V9.5c0-2.75.75-5.25 3-7Zm-3 7l-1.75 2.25v2.75L4.5 13m6-3.5l1.75 2.25v2.75L10.5 13M6 13h3l.5 2h-4Z");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.we_b95bsc {
  d: path("M6.25 7.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm-.5 7.5h3.5c0 2.25-.5 3.75-1.75 5.5c-1.25-1.75-1.75-3.25-1.75-5.5Zm9.75-.25h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

</style>
