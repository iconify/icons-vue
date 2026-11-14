<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wbfivcc8o"/><path class="lo970fxfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-at-risk" /></template>
<style>
.lo970fxfb {
  d: path("M8 21.5V17h3v4.5M7 7h.01M12 7h.01M7 11.5h.01m4.99 0h.01m6.99 3V18m0 3h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wbfivcc8o {
  d: path("M3 2.5h13v19H3Z");
}

</style>
