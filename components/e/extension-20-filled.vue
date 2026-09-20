<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cbasxm-uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:extension-20-filled" /></template>
<style>
.cbasxm-uy {
  fill: currentColor;
  d: path("M11 2a2 2 0 0 0-2 2H6.5A1.5 1.5 0 0 0 5 5.5V8a2 2 0 1 0 0 4v2.5A1.5 1.5 0 0 0 6.5 16H9a2 2 0 1 0 4 0h2.5a1.5 1.5 0 0 0 1.5-1.5V12h-1a2 2 0 1 1 0-4h1V5.5A1.5 1.5 0 0 0 15.5 4H13a2 2 0 0 0-2-2");
}

</style>
