<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gpdr4m3uh"/><path class="u70g162xj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balloon-bouquet-gift" /></template>
<style>
.gpdr4m3uh {
  d: path("M6.5 14.5h11v7h-11Zm-2.75-8a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm6-2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm6 2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.u70g162xj {
  d: path("m6 8.75l6 5.75l6-5.75m-6-2V21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
