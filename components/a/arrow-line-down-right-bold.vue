<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ip4pqxzrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-line-down-right-bold" /></template>
<style>
.ip4pqxzrr {
  fill: currentColor;
  d: path("M228 40a12 12 0 0 1-12 12H40a12 12 0 0 1 0-24h176a12 12 0 0 1 12 12m-36 52a12 12 0 0 0-12 12v67L88.49 79.51a12 12 0 0 0-17 17L163 188H96a12 12 0 0 0 0 24h96a12 12 0 0 0 12-12v-96a12 12 0 0 0-12-12");
}

</style>
