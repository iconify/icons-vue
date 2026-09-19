<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sndizkbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-filter-list-off" /></template>
<style>
.sndizkbnm {
  fill: currentColor;
  d: path("M10.83 8H21V6H8.83zm5 5H18v-2h-4.17zM14 16.83V18h-4v-2h3.17l-3-3H6v-2h2.17l-3-3H3V6h.17L1.39 4.22L2.8 2.81l18.38 18.38l-1.41 1.41z");
}

</style>
