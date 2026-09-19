<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7j054bev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-bedtime" /></template>
<style>
.w7j054bev {
  fill: currentColor;
  d: path("M12.34 2.02C6.59 1.82 2 6.42 2 12c0 5.52 4.48 10 10 10c3.71 0 6.93-2.02 8.66-5.02c-7.51-.25-12.09-8.43-8.32-14.96");
}

</style>
