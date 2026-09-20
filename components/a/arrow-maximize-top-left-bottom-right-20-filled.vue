<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="id18h52ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-top-left-bottom-right-20-filled" /></template>
<style>
.id18h52ud {
  fill: currentColor;
  d: path("M10.25 3.5a.75.75 0 0 1 0 1.5H6.06L15 13.94V9.75a.75.75 0 0 1 1.5 0v6a.75.75 0 0 1-.75.75h-6a.75.75 0 0 1 0-1.5h4.19L5 6.06v4.19a.75.75 0 0 1-1.5 0v-6a.75.75 0 0 1 .75-.75z");
}

</style>
