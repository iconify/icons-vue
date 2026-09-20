<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d5wecvbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-treemap-20-regular" /></template>
<style>
.d5wecvbkk {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm1 1v12H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zm1 12v-3h8v1a2 2 0 0 1-2 2zm8-4H8V4h6a2 2 0 0 1 2 2z");
}

</style>
