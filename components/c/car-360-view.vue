<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gknij3bav"/><path class="t_mqd5bgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-360-view" /></template>
<style>
.gknij3bav {
  d: path("M7 10q0-1.25 1-1.5l1-2.75Q9.25 5 10 5h4q.75 0 1 .75l1 2.75q1 .25 1 1.5v2.5H7Zm1.75 2.5V14m6.5-1.5V14M5.5 12.75c-1.9.75-3 1.75-3 3c0 2.5 4.25 4.5 9.5 4.5s9.5-2 9.5-4.5c0-1.25-1.1-2.25-3-3");
}

.t_mqd5bgi {
  d: path("M17.25 18L15 20.25L17.25 22");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
