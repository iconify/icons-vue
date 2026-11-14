<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ak83g5bqx"/><path class="bi_2y5bap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drinking-age" /></template>
<style>
.ak83g5bqx {
  d: path("M13.4 19H2.5V5h19v6.7m-19-2.2h19M6 15h3");
}

.bi_2y5bap {
  d: path("M15.5 14.5H21c0 3-1.5 4-2.75 4s-2.75-1-2.75-4Zm2.75 4v3m-2 0h4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
