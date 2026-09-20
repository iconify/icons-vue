<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":276};
const content = `<path class="qu8xcsbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:databricks-icon" /></template>
<style>
.qu8xcsbze {
  fill: var(--svg-color--ee3d2c, #ee3d2c);
  d: path("m242.284 113.629l-114.158 64.268l-122.24-68.672L0 112.399v49.864l128.126 71.834l114.145-64.017v26.387l-114.145 64.281l-122.24-68.672L0 195.25v8.545l128.126 71.846L256 203.795v-49.851l-5.886-3.174l-121.988 68.42l-114.41-64.016v-26.4l114.41 64.016L256 120.97V71.82l-6.375-3.664l-121.499 68.183L19.602 75.735l108.524-60.842l89.16 50.089l7.843-4.391V54.48L128.126 0L0 71.833v7.831l128.126 71.846l114.145-64.281z");
}

</style>
