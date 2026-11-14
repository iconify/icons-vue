<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yoot4wbny"/><path class="ggrjlsb_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forensic-report" /></template>
<style>
.ggrjlsb_h {
  d: path("M16 13.5h4m-3.25 0v3l-2.5 4.75h7.25l-2.25-4.75v-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yoot4wbny {
  d: path("M11 21.5H4.5v-19h15v8.2M8 7h8m-8 4h5.2M8 15h3.5");
}

</style>
