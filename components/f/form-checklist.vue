<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="l-9k33bgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:form-checklist" /></template>
<style>
.l-9k33bgn {
  d: path("m6.75 7l1.5 1.5l2.75-3m-4.25 6.75l1.5 1.5l2.75-3M7 15.5h3.5V19H7ZM13.5 7H17m-3.5 5.25H17m-3.5 5H17");
}

.oeucrxbku {
  d: path("M3.5 2.5h17v19h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
