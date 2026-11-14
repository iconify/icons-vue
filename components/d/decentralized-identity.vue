<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tsscxrbxn"/><path class="ztl0l6a8k"/><path class="hecannbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decentralized-identity" /></template>
<style>
.hecannbus {
  d: path("m15.745 17.03l3.535-3.535l2.475 2.475l-3.535 3.535Z");
}

.tsscxrbxn {
  d: path("M9.8 19.5H2.5v-15h19v7.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ztl0l6a8k {
  d: path("M6.5 9.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5 17q0-2.5 3.5-2.5q3.386 0 3.496 2.34M14.5 9.5h4m-5.005 9.78l3.535-3.535l2.475 2.475l-3.535 3.535Z");
}

</style>
