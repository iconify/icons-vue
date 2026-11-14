<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dkiyrmblm"/><path class="nag64nc0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-dryer-cool" /></template>
<style>
.dkiyrmblm {
  d: path("M7 3.5L15.5 5v6L7 12.5a4.5 4.5 0 0 1 0-9Z");
}

.nag64nc0k {
  d: path("M6.25 12.5V20a1.5 1.5 0 0 0 1.5 1.5h.5a1.5 1.5 0 0 0 1.5-1.5v-8m8.75-6h3m-3 4h3M18 15v6m-2.5-4.5l5 3m-5 0l5-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
