<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vrecuweet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-down-left-thin" /></template>
<style>
.vrecuweet {
  fill: currentColor;
  d: path("M228 56a100.11 100.11 0 0 1-100 100H41.66l41.17 41.17a4 4 0 0 1-5.66 5.66l-48-48a4 4 0 0 1 0-5.66l48-48a4 4 0 0 1 5.66 5.66L41.66 148H128a92.1 92.1 0 0 0 92-92a4 4 0 0 1 8 0");
}

</style>
