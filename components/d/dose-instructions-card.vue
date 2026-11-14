<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rq6975bfj"/><path class="m_wgazl2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-instructions-card" /></template>
<style>
.m_wgazl2o {
  d: path("m19.5 14.5l2 2l-2 2");
}

.rq6975bfj {
  d: path("M12.2 21H3V2.5h14v10.6M3 7h14M6.5 11h7m-7 4h4m4.5 6.5V20a3.5 3.5 0 0 1 3.5-3.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
