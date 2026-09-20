<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vgjqq014c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-circle-down-right-bold" /></template>
<style>
.vgjqq014c {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m44-100v48a12 12 0 0 1-12 12h-48a12 12 0 0 1 0-24h19l-43.49-43.51a12 12 0 0 1 17-17L148 131v-19a12 12 0 0 1 24 0");
}

</style>
