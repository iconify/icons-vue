<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lqx0yihec"/><path class="yvkn_lbzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doctors-office" /></template>
<style>
.lqx0yihec {
  d: path("M5 21.5v-17c0-1.1.9-2 2-2h10c1.1 0 2 .9 2 2v17m-16.5 0h19m-7-10.5h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yvkn_lbzc {
  d: path("M12.5 11v1.75c0 1.25 1 2.25 2 2.25s2-1 2-2.25V11m-2 4v1.75M13.25 18a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
