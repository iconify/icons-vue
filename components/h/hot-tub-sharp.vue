<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="n1dpotjsn"/><path class="xgia8cbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hot-tub-sharp" /></template>
<style>
.n1dpotjsn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.75L6.397 4L7.5 5.25L8.603 6.5L7.5 7.75m4.5-5L10.897 4L12 5.25l1.103 1.25L12 7.75m4.5-5L15.397 4L16.5 5.25l1.103 1.25L16.5 7.75m-13.75 3h18.5v10.5H2.75zm0 3.5h18.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.xgia8cbty {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17.75h.01m3.99 0h.01m3.99 0h.01");
}

</style>
