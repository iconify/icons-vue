<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i93y9wwiw"/><path class="qgjd_yblb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clock-minus" /></template>
<style>
.i93y9wwiw {
  d: path("M12.25 21.5a9.5 9.5 0 1 1 9.25-9.25h-7.25a2 2 0 0 0-2 2Z");
}

.qgjd_yblb {
  d: path("M10.75 6.25v4.5h-3.5M15 18h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
