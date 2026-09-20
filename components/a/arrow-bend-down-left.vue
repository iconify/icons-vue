<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vv0r_obbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-down-left" /></template>
<style>
.vv0r_obbt {
  fill: currentColor;
  d: path("M232 56a104.11 104.11 0 0 1-104 104H51.31l34.35 34.34a8 8 0 0 1-11.32 11.32l-48-48a8 8 0 0 1 0-11.32l48-48a8 8 0 0 1 11.32 11.32L51.31 144H128a88.1 88.1 0 0 0 88-88a8 8 0 0 1 16 0");
}

</style>
