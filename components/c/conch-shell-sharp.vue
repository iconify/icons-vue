<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="frsw0acqd"/><path class="utuwb-7jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conch-shell-sharp" /></template>
<style>
.frsw0acqd {
  d: path("m4.93 4.2l.64.1l1.18.2l.25.63l.25.62l1.2-.11l.35-.03L10 5.5l.38.75l.37.75l1.19-.14l1.87-.22L15 6.5l.97.71l2.81 2.08l.97.71l.24 1.18l.52 2.64l.24 1.18l-.24 1.17l-.77 3.66L19.5 21l-1.07-.54l-2.36-1.17l-1.07-.54l-1.2-.05l-3.1-.15l-1.2-.05l-.82-.87l-2.61-2.76l-.82-.87l-.11-1.2l-.28-3.1q-.11-1.2-.37-2.37l-.48-2.16L3.75 4z");
}

.utuwb-7jg {
  d: path("m15.5 10.5l2.829 2.021l-.829 3.729M6.25 9l1.974-.395L9.75 9.75m-2 1.75l3-.75L13 13");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
