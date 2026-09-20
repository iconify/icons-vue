<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ddwhpcbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-32-regular" /></template>
<style>
.ddwhpcbzl {
  fill: currentColor;
  d: path("M5.293 20.707a1 1 0 0 0 1.414 0L16 11.414l9.293 9.293a1 1 0 0 0 1.414-1.414l-10-10a1 1 0 0 0-1.414 0l-10 10a1 1 0 0 0 0 1.414");
}

</style>
