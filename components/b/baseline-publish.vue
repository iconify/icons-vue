<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yizktvb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-publish" /></template>
<style>
.yizktvb6m {
  fill: currentColor;
  d: path("M5 4v2h14V4zm0 10h4v6h6v-6h4l-7-7z");
}

</style>
