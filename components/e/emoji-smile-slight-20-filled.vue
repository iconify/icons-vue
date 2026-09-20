<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hkb4adb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-smile-slight-20-filled" /></template>
<style>
.hkb4adb2r {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16M8.5 8.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m4-1a1 1 0 1 1 0 2a1 1 0 0 1 0-2m-4.026 5.553c.416.208.961.322 1.526.322s1.11-.114 1.526-.322a.5.5 0 1 1 .448.894c-.584.292-1.289.428-1.974.428s-1.39-.136-1.974-.428a.5.5 0 1 1 .448-.894");
}

</style>
