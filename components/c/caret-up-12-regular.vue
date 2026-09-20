<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yij-yizja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-up-12-regular" /></template>
<style>
.yij-yizja {
  fill: currentColor;
  d: path("M3.076 7.383A1 1 0 0 0 4 8h4a1 1 0 0 0 .707-1.707l-2-2a1 1 0 0 0-1.414 0l-2 2a1 1 0 0 0-.217 1.09M4 7l1.823-1.823a.25.25 0 0 1 .354 0L8 7z");
}

</style>
