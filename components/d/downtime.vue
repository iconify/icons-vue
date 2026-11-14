<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cl14njbkf"/><path class="ggyzo300o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:downtime" /></template>
<style>
.cl14njbkf {
  d: path("m14.937 13.792l-.187-.042l-1 1l.5 2.25l-2 .75L11 16H9.5l-1.25 1.75l-2-.75l.5-2.25l-1-1l-2.25.5l-.75-2L4.5 11V9.5L2.75 8.25l.75-2l2.25.5l1-1l-.5-2.25l2-.75L9.5 4.5H11l1.25-1.75l2 .75l-.5 2.25l1 1l2.25-.5l.75 2L16 9.5V11l1.75 1.25l-.544 1.451");
}

.ggyzo300o {
  d: path("M7.75 10.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm10 6.25v5.25m3.5-5.25v5.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
