<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jv32l8iai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-unfold-less" /></template>
<style>
.jv32l8iai {
  fill: currentColor;
  d: path("M7.41 18.59L8.83 20L12 16.83L15.17 20l1.41-1.41L12 14zm9.18-13.18L15.17 4L12 7.17L8.83 4L7.41 5.41L12 10z");
}

</style>
