<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jbscaf7qy"/><path class="r4vkab8dm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exit-page" /></template>
<style>
.jbscaf7qy {
  d: path("M11.1 21.5H3.5v-19h17v9.1M3.5 7h17m-14-2.25h.01m2.74 0h.01M7 11h10M7 14.5h5m2.75 6.75l5.75-5.75");
}

.r4vkab8dm {
  d: path("M16.25 15.25h4.5v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
