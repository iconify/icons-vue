<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytzqwrbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-between-down-24-filled" /></template>
<style>
.ytzqwrbnj {
  fill: currentColor;
  d: path("M6.5 2.25a1 1 0 0 0-2 0v.25A2.5 2.5 0 0 0 7 5h10a2.5 2.5 0 0 0 2.5-2.5v-.25a1 1 0 1 0-2 0v.25a.5.5 0 0 1-.5.5H7a.5.5 0 0 1-.5-.5zm5.5 4a1 1 0 0 1 1 1v7.086l2.793-2.793a1 1 0 0 1 1.414 1.414l-4.5 4.5a1 1 0 0 1-1.414 0l-4.5-4.5a1 1 0 1 1 1.414-1.414L11 14.336V7.25a1 1 0 0 1 1-1M4.5 21.5A2.5 2.5 0 0 1 7 19h10a2.5 2.5 0 0 1 2.5 2.5v.25a1 1 0 1 1-2 0v-.25a.5.5 0 0 0-.5-.5H7a.5.5 0 0 0-.5.5v.25a1 1 0 1 1-2 0z");
}

</style>
