<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6g9mgvdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-line-spacing-outline" /></template>
<style>
.s6g9mgvdj {
  fill: currentColor;
  d: path("m6 20l-4-4l1.4-1.4L5 16.15v-8.3L3.4 9.4L2 8l4-4l4 4l-1.4 1.4L7 7.85v8.3l1.6-1.55L10 16zm6-1v-2h10v2zm0-6v-2h10v2zm0-6V5h10v2z");
}

</style>
