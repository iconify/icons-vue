<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wu59p4v0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:identification-badge-fill" /></template>
<style>
.wu59p4v0i {
  fill: currentColor;
  d: path("M200 24H56a16 16 0 0 0-16 16v176a16 16 0 0 0 16 16h144a16 16 0 0 0 16-16V40a16 16 0 0 0-16-16M96 48h64a8 8 0 0 1 0 16H96a8 8 0 0 1 0-16m84.81 150.4a8 8 0 0 1-11.21-1.6a52 52 0 0 0-83.2 0a8 8 0 1 1-12.8-9.6a67.9 67.9 0 0 1 27.4-21.69a40 40 0 1 1 53.94 0a67.9 67.9 0 0 1 27.46 21.69a8 8 0 0 1-1.59 11.2M152 136a24 24 0 1 1-24-24a24 24 0 0 1 24 24");
}

</style>
