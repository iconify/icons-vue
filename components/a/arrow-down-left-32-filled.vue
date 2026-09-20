<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hyf0fsbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-32-filled" /></template>
<style>
.hyf0fsbuy {
  fill: currentColor;
  d: path("M16.75 29a1.25 1.25 0 1 0 0-2.5H7.268L28.634 5.134a1.25 1.25 0 0 0-1.768-1.768L5.5 24.732V15.25a1.25 1.25 0 0 0-2.5 0v12.5c0 .69.56 1.25 1.25 1.25z");
}

</style>
