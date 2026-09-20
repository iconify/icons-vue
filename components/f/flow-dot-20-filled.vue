<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uv7v9klnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-dot-20-filled" /></template>
<style>
.uv7v9klnt {
  fill: currentColor;
  d: path("M5 2.75A2 2 0 0 1 6.854 4h6.896a3.25 3.25 0 0 1 0 6.5h-7.5a1.75 1.75 0 1 0 0 3.5h6.897a2 2 0 1 1 0 1.5H6.25a3.25 3.25 0 0 1 0-6.5h7.5a1.75 1.75 0 1 0 0-3.5H6.854A2 2 0 1 1 5 2.75");
}

</style>
