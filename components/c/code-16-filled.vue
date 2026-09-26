<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="isbesvbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-16-filled" /></template>
<style>
.isbesvbkm {
  fill: currentColor;
  d: path("M9.544 1.496a.751.751 0 0 1 1.412.508l-4.5 12.5a.751.751 0 0 1-1.412-.508zm1.676 2.973a.75.75 0 0 1 1.06 0l3 3a.75.75 0 0 1 0 1.06l-3 3a.75.75 0 0 1-1.06-1.06L13.69 8l-2.47-2.47a.75.75 0 0 1 0-1.06m-7.772.024a.75.75 0 0 1 1.105 1.013L2.267 8l2.286 2.493a.75.75 0 0 1-1.105 1.013l-2.75-3a.75.75 0 0 1 0-1.013z");
}

</style>
