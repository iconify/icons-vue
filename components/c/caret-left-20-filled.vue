<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szsy4g-3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-left-20-filled" /></template>
<style>
.szsy4g-3y {
  fill: currentColor;
  d: path("M13 14.204a1 1 0 0 1-1.628.778l-4.723-3.815a1.5 1.5 0 0 1 0-2.334l4.723-3.814A1 1 0 0 1 13 5.797z");
}

</style>
