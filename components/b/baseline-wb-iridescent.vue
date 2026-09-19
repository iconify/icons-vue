<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxf0whb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-wb-iridescent" /></template>
<style>
.uxf0whb8e {
  fill: currentColor;
  d: path("M5 14.5h14v-6H5zM11 .55V3.5h2V.55zm8.04 2.5l-1.79 1.79l1.41 1.41l1.8-1.79zM13 22.45V19.5h-2v2.95zm7.45-3.91l-1.8-1.79l-1.41 1.41l1.79 1.8zM3.55 4.46l1.79 1.79l1.41-1.41l-1.79-1.79zm1.41 15.49l1.79-1.8l-1.41-1.41l-1.79 1.79z");
}

</style>
