<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lc-wjvbte"/><path class="a2ayupb2v"/><path class="po5hu0s_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-flap" /></template>
<style>
.a2ayupb2v {
  d: path("M7.5 12h9v6.75h-9Z");
}

.lc-wjvbte {
  d: path("M4 2.5h16v19H4Zm12.5 6h.01");
}

.po5hu0s_s {
  d: path("m7.5 12l1.75 4.25h5.5L16.5 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
