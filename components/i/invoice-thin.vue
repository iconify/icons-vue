<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bfhny15sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:invoice-thin" /></template>
<style>
.bfhny15sk {
  fill: currentColor;
  d: path("M28 124a4 4 0 0 1 0-8h28a12 12 0 0 0 0-24H40a20 20 0 0 1 0-40h4v-4a4 4 0 0 1 8 0v4h12a4 4 0 0 1 0 8H40a12 12 0 0 0 0 24h16a20 20 0 0 1 0 40h-4v4a4 4 0 0 1-8 0v-4Zm200-68v136a12 12 0 0 1-12 12H40a12 12 0 0 1-12-12v-40a4 4 0 0 1 8 0v40a4 4 0 0 0 4 4h124v-40H80a4 4 0 0 1 0-8h84v-40h-60a4 4 0 0 1 0-8h116V60H96a4 4 0 0 1 0-8h128a4 4 0 0 1 4 4m-56 92h48v-40h-48Zm48 44v-36h-48v40h44a4 4 0 0 0 4-4");
}

</style>
