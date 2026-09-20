<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lkvbfykiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-32-regular" /></template>
<style>
.lkvbfykiq {
  fill: currentColor;
  d: path("M16 3a1 1 0 0 1 1 1v21.586l8.293-8.293a1 1 0 0 1 1.414 1.414l-10 10a1 1 0 0 1-1.414 0l-10-10a1 1 0 1 1 1.414-1.414L15 25.586V4a1 1 0 0 1 1-1");
}

</style>
