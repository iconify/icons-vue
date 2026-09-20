<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eutjk3bqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:copyleft-bold" /></template>
<style>
.eutjk3bqq {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m52-84a52 52 0 0 1-93.59 31.21a12 12 0 1 1 19.18-14.41a28 28 0 1 0 0-33.6a12 12 0 1 1-19.18-14.41A52 52 0 0 1 180 128");
}

</style>
