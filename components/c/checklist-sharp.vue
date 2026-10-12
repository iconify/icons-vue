<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cptvh_bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checklist-sharp" /></template>
<style>
.cptvh_bgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 5.25l1.5 1.5l2.75-3m-4.25 8l1.5 1.5l2.75-3m-4.25 8l1.5 1.5l2.75-3M11.5 5.5h9.75M11.5 12h9.75m-9.75 6.5h9.75");
}

</style>
