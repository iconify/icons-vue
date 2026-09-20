<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="by1s2nban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-32-regular" /></template>
<style>
.by1s2nban {
  fill: currentColor;
  d: path("M15 3a1 1 0 1 0 0 2h10.585L3.297 27.289a1 1 0 1 0 1.414 1.414L27 6.414V17a1 1 0 1 0 2 0V4a1 1 0 0 0-1-1z");
}

</style>
