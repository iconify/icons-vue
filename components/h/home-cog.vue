<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5q4_bbdl"/><path class="o0u68tbtw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-cog" /></template>
<style>
.o0u68tbtw {
  d: path("m11.372 11.839l.008-1.284h1.24l.008 1.284l.929.537l1.116-.635l.62 1.073l-1.108.649v1.074l1.108.649l-.62 1.073l-1.116-.635l-.929.537l-.008 1.284h-1.24l-.008-1.284l-.929-.537l-1.116.635l-.62-1.073l1.108-.649v-1.074l-1.108-.649l.62-1.073l1.116.635Z");
}

.q5q4_bbdl {
  d: path("m4 10.5l8-7l8 7V20H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
