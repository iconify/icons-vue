<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="envo3lbfq"/><path class="dd_rdbb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cling-wrap-sharp" /></template>
<style>
.dd_rdbb1o {
  d: path("M5.5 8.75L6.8 7.5l1.3 1.25L9.4 7.5l1.3 1.25L12 7.5l1.3 1.25l1.3-1.25l1.3 1.25l1.3-1.25l1.3 1.25m-12.5 3h12.75l-.2.72l-2.1 7.56l-.2.72H2.75l.2-.72l2.1-7.56l.2-.72z");
}

.envo3lbfq {
  d: path("M2.75 4.25h18.5v7.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
