<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wid13xjkn"/><path class="ft_gs2lgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:machine-telemetry" /></template>
<style>
.ft_gs2lgf {
  d: path("M7.75 17.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-5.5 1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM14.5 7a3 3 0 0 1 3 3m-3-6.5A6.5 6.5 0 0 1 21 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wid13xjkn {
  d: path("M2.5 13.75h5.25v2.75H2.5Zm5.25 0V10a.75.75 0 0 1 .75-.75h3.75l1 5.25");
}

</style>
