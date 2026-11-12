<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tj0-nnlxp"/><path class="d7osq547d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:intersect-minimalistic-line-duotone" /></template>
<style>
.d7osq547d {
  d: path("M12.9994 14.9827C11.4463 14.9358 10.5199 14.7625 9.87872 14.1213C9.23752 13.4801 9.06422 12.5537 9.01732 11.0006C8.98892 10.0573 8.97472 9.58562 9.28012 9.28012C9.58562 8.97472 10.0573 8.98892 11.0006 9.01732C12.5537 9.06422 13.4801 9.23752 14.1213 9.87872C14.7625 10.5199 14.9358 11.4463 14.9827 12.9994C15.0111 13.9427 15.0253 14.4144 14.7199 14.7199C14.4144 15.0253 13.9427 15.0111 12.9994 14.9827Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tj0-nnlxp {
  d: path("M9.0173 6C9.0641 4.4466 9.2374 3.52 9.8787 2.8787C10.7574 2 12.1716 2 15 2H16C18.8284 2 20.2426 2 21.1213 2.8787C22 3.7574 22 5.1716 22 8V9C22 11.8284 22 13.2426 21.1213 14.1213C20.48 14.7626 19.5534 14.9359 18 14.9827M6 9.0173C4.4466 9.0641 3.52 9.2374 2.8787 9.8787C2 10.7574 2 12.1716 2 15V16C2 18.8284 2 20.2426 2.8787 21.1213C3.7574 22 5.1716 22 8 22H9C11.8284 22 13.2426 22 14.1213 21.1213C14.7626 20.48 14.9359 19.5534 14.9827 18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
