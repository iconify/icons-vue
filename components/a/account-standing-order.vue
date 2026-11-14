<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sflw2-bel"/><path class="zjpa3ob-p"/><path class="m838ucczp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-standing-order" /></template>
<style>
.m838ucczp {
  d: path("m15.5 12.25l2 2l-2 2");
}

.sflw2-bel {
  d: path("M12.4 21.5H4.5v-19h15v9m-11-9v19m3-14.5h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zjpa3ob-p {
  d: path("M20.531 16a3.5 3.5 0 1 1-3.031-1.75");
}

</style>
