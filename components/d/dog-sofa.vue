<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zyb9o3b7k"/><path class="khw5ntbzq"/><path class="drdeqbbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-sofa" /></template>
<style>
.drdeqbbxo {
  d: path("M7.75 15v-2.5L8.5 10l1.75 1.5c2.25-2 6-1 6 3.5");
}

.khw5ntbzq {
  d: path("M3.75 11V6.5a2 2 0 0 1 2-2h12.5a2 2 0 0 1 2 2V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyb9o3b7k {
  d: path("M2.5 19.5v-7.25a1.25 1.25 0 0 1 2.5 0V15h14v-2.75a1.25 1.25 0 0 1 2.5 0v7.25Z");
}

</style>
