<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h3ebh_fmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-enter-up-20-regular" /></template>
<style>
.h3ebh_fmn {
  fill: currentColor;
  d: path("M8.864 2.157a.5.5 0 0 0-.728 0l-4 4.25a.5.5 0 0 0 .728.686L8 3.76V15a3 3 0 0 0 3 3h4.5a.5.5 0 0 0 0-1H11a2 2 0 0 1-2-2V3.76l3.136 3.333a.5.5 0 0 0 .728-.686z");
}

</style>
