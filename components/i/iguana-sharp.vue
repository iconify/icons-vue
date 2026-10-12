<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="a-npd_-0j"/><path class="u-6donb9h"/><path class="qvx_uacff"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iguana-sharp" /></template>
<style>
.a-npd_-0j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11V9.363L4.75 9.1l3.5-.35l2.008-.241L11.5 10h4.25c2 0 3.5 1.5 3.5 3.25v2.25H11l-1.5 2.25L8.25 15c-1.5-.25-2.75-1.5-4.35-2.4l-.9-.491z");
}

.qvx_uacff {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10.75h.01");
}

.u-6donb9h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.5 10l1-2l1 2l1-2l1 2l1-2l1 2.4m-5 5.1l-.5 3m4.5-3l.75 3m2-5.25c1.5 1 2 2.5 1.75 4.25l-.412 2.471l-2.338.779");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
