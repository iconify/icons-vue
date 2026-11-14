<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zybjpbn6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-translation" /></template>
<style>
.zybjpbn6f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H11V12H2.5ZM13 12h8.5v9.5H13ZM5.25 6h3m-3 3h2M16 15.5h3m-3 3h2M16.25 3.75L14 6l2.25 2.25M14 6h6.5m-2.25-2.25L20.5 6l-2.25 2.25");
}

</style>
