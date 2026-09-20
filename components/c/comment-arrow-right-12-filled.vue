<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wbt-xth0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-arrow-right-12-filled" /></template>
<style>
.wbt-xth0u {
  fill: currentColor;
  d: path("M12 3.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0M6.5 3a.5.5 0 0 0 0 1h2.793l-.647.646a.5.5 0 1 0 .708.708l1.5-1.5A.5.5 0 0 0 11 3.503v-.006a.5.5 0 0 0-.146-.35l-1.5-1.5a.5.5 0 1 0-.708.707L9.293 3zm2 5a4.5 4.5 0 0 0 2.484-.747A2 2 0 0 1 9 9H6.651l-2.874 1.916A.5.5 0 0 1 3 10.5V9a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1.758A4.5 4.5 0 0 0 8.5 8");
}

</style>
