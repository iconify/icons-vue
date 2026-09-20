<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g81e20bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hive-sharp" /></template>
<style>
.g81e20bcj {
  fill: currentColor;
  d: path("m16.275 11.5l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3zm-5.95 3.5l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3zm0-7l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3zm-5.95 3.5l-1.7-3l1.7-3h3.35l1.625 3l-1.625 3zm0 7l-1.7-3l1.7-3h3.35l1.625 3l-1.625 3zm6.05 3.5l-1.8-3l1.7-3h3.35l1.7 3l-1.7 3zm5.85-3.5l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3z");
}

</style>
