<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i64cj8d_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-double-up-left-fill" /></template>
<style>
.i64cj8d_h {
  fill: currentColor;
  d: path("M85.66 146.34a8 8 0 0 1-11.32 11.32l-48-48a8 8 0 0 1 0-11.32l48-48a8 8 0 0 1 11.32 11.32L43.31 104ZM136 96.3V56a8 8 0 0 0-13.66-5.66l-48 48a8 8 0 0 0 0 11.32l48 48A8 8 0 0 0 136 152v-39.63A88.11 88.11 0 0 1 216 200a8 8 0 0 0 16 0a104.15 104.15 0 0 0-96-103.7");
}

</style>
