<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vw2tkd75o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-circle-down-left-bold" /></template>
<style>
.vw2tkd75o {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m40.49-124.49a12 12 0 0 1 0 17L125 148h19a12 12 0 0 1 0 24H96a12 12 0 0 1-12-12v-48a12 12 0 0 1 24 0v19l43.51-43.52a12 12 0 0 1 16.98.03");
}

</style>
