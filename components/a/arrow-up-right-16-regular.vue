<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e1xd5d_zl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-16-regular" /></template>
<style>
.e1xd5d_zl {
  fill: currentColor;
  d: path("M7.5 3a.5.5 0 0 1 0-1h6a.5.5 0 0 1 .5.5v6a.5.5 0 0 1-1 0V3.707L2.854 13.854a.5.5 0 0 1-.708-.708L12.293 3z");
}

</style>
