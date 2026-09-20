<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zrhcjqxuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-smile-slight-20-regular" /></template>
<style>
.zrhcjqxuh {
  fill: currentColor;
  d: path("M13.5 8.5a1 1 0 1 0-2 0a1 1 0 0 0 2 0m-5 0a1 1 0 1 0-2 0a1 1 0 0 0 2 0m-.026 4.553a.5.5 0 1 0-.448.894c.584.292 1.289.428 1.974.428s1.39-.136 1.974-.428a.5.5 0 1 0-.448-.894c-.416.208-.961.322-1.526.322s-1.11-.114-1.526-.322M18 10a8 8 0 1 0-16 0a8 8 0 0 0 16 0M3 10a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
