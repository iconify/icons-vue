<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6u8ygnbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-upload" /></template>
<style>
.k6u8ygnbi {
  fill: currentColor;
  d: path("M5 20h14v-2H5zm0-10h4v6h6v-6h4l-7-7z");
}

</style>
