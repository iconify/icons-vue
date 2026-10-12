<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8gqv1nlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-download-sharp" /></template>
<style>
.f8gqv1nlb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 19.25h-9V4.75h7.1l.6.8L11.55 7l.6.8h9.1v4.75m-18.5-1.8h12m2.75 3v6.5m-2.5-2.5l2.5 2.5l2.5-2.5");
}

</style>
