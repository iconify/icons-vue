<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ntm9idbzh"/><path class="ds-axhblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bicycle-front" /></template>
<style>
.ds-axhblu {
  d: path("M7.25 15.5V7h9.5v8.5M12 4.25V7M2.5 2.75q1 1.5 2.5 1.5h14q1.5 0 2.5-1.5");
}

.ntm9idbzh {
  d: path("M10 15.75a2 5.75 0 1 0 4 0a2 5.75 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
