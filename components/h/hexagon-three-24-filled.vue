<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie42zb2zb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hexagon-three-24-filled" /></template>
<style>
.ie42zb2zb {
  fill: currentColor;
  d: path("M6.343 2a1.75 1.75 0 0 0-1.516.875l-1.588 2.75a1.75 1.75 0 0 0 0 1.75l1.588 2.75c.313.541.89.875 1.516.875h3.175a1.75 1.75 0 0 0 1.516-.875l1.587-2.75a1.75 1.75 0 0 0 0-1.75l-1.587-2.75A1.75 1.75 0 0 0 9.518 2zM4.827 13.875A1.75 1.75 0 0 1 6.343 13h3.175a1.75 1.75 0 0 1 1.516.875l1.587 2.75a1.75 1.75 0 0 1 0 1.75l-1.587 2.75A1.75 1.75 0 0 1 9.518 22H6.343a1.75 1.75 0 0 1-1.516-.875l-1.588-2.75a1.75 1.75 0 0 1 0-1.75zm9.5-5.5a1.75 1.75 0 0 1 1.516-.875h3.175a1.75 1.75 0 0 1 1.516.875l1.587 2.75a1.75 1.75 0 0 1 0 1.75l-1.587 2.75a1.75 1.75 0 0 1-1.516.875h-3.175a1.75 1.75 0 0 1-1.516-.875l-1.588-2.75a1.75 1.75 0 0 1 0-1.75z");
}

</style>
