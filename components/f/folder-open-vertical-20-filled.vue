<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j2tjzk5fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-open-vertical-20-filled" /></template>
<style>
.j2tjzk5fs {
  fill: currentColor;
  d: path("M17 4.5A2.5 2.5 0 0 0 14.5 2H7.529l2.716 1.568a3.5 3.5 0 0 1 1.75 3.031V16h.505a2.5 2.5 0 0 0 2.5-2.5V9.707l1.56-1.56A1.5 1.5 0 0 0 17 7.085zm-7.255-.066a2.5 2.5 0 0 1 1.25 2.165v10.396c0 1.54-1.667 2.502-3 1.732L4.25 16.565A2.5 2.5 0 0 1 3 14.4V4.004c0-1.54 1.667-2.502 3-1.732z");
}

</style>
