<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e16j8ccwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:desktop-bold" /></template>
<style>
.e16j8ccwv {
  fill: currentColor;
  d: path("M208 36H48a28 28 0 0 0-28 28v108a28 28 0 0 0 28 28h68v12H96a12 12 0 0 0 0 24h64a12 12 0 0 0 0-24h-20v-12h68a28 28 0 0 0 28-28V64a28 28 0 0 0-28-28M48 60h160a4 4 0 0 1 4 4v72H44V64a4 4 0 0 1 4-4m160 116H48a4 4 0 0 1-4-4v-12h168v12a4 4 0 0 1-4 4");
}

</style>
