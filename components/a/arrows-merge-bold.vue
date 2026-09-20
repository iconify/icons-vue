<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h3sod8rzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrows-merge-bold" /></template>
<style>
.h3sod8rzv {
  fill: currentColor;
  d: path("M196 40v64a12 12 0 0 1-3.51 8.49L140 165v38l11.51-11.52a12 12 0 0 1 17 17l-32 32a12 12 0 0 1-17 0l-32-32a12 12 0 0 1 17-17L116 203v-38l-52.49-52.51A12 12 0 0 1 60 104V40a12 12 0 0 1 24 0v59l44 44l44-44V40a12 12 0 0 1 24 0");
}

</style>
