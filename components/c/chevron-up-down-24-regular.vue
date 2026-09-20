<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxd_bnbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-down-24-regular" /></template>
<style>
.oxd_bnbqy {
  fill: currentColor;
  d: path("M12.54 2.23a.75.75 0 0 0-1.08 0l-6.25 6.5a.75.75 0 1 0 1.08 1.04L12 3.832l5.71 5.938a.75.75 0 1 0 1.08-1.04zm0 19.54a.75.75 0 0 1-1.08 0l-6.25-6.5a.75.75 0 1 1 1.08-1.04L12 20.168l5.71-5.938a.75.75 0 1 1 1.08 1.04z");
}

</style>
