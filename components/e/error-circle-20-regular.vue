<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wwwg1mb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:error-circle-20-regular" /></template>
<style>
.wwwg1mb2n {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14m0 9.5a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5M10 6a.5.5 0 0 1 .492.41l.008.09V11a.5.5 0 0 1-.992.09L9.5 11V6.5A.5.5 0 0 1 10 6");
}

</style>
