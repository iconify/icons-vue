<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ft8mn2abn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:battery-plus-vertical-light" /></template>
<style>
.ft8mn2abn {
  fill: currentColor;
  d: path("M90 8a6 6 0 0 1 6-6h64a6 6 0 0 1 0 12H96a6 6 0 0 1-6-6m108 48v168a22 22 0 0 1-22 22H80a22 22 0 0 1-22-22V56a22 22 0 0 1 22-22h96a22 22 0 0 1 22 22m-12 0a10 10 0 0 0-10-10H80a10 10 0 0 0-10 10v168a10 10 0 0 0 10 10h96a10 10 0 0 0 10-10Zm-30 78h-22v-22a6 6 0 0 0-12 0v22h-22a6 6 0 0 0 0 12h22v22a6 6 0 0 0 12 0v-22h22a6 6 0 0 0 0-12");
}

</style>
