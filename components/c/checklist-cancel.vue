<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zpzay42zj"/><path class="kvv84sb-l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:checklist-cancel" /></template>
<style>
.kvv84sb-l {
  d: path("M3.75 4.5L5.25 6L8.5 2.5m2 2.25H21m-10.5 7h4.8m.4 0h4.6m.4 0h.3m-5.5 3.75l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zpzay42zj {
  d: path("M2.75 2.75H7V7H2.75Zm0 7H7V14H2.75Zm0 7H7V21H2.75Z");
}

</style>
