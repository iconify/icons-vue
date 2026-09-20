<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nx6m9xzzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-arrow-right-12-regular" /></template>
<style>
.nx6m9xzzt {
  fill: currentColor;
  d: path("M12 3.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0M6.5 3a.5.5 0 0 0 0 1h2.793l-.647.646a.5.5 0 1 0 .708.708l1.5-1.5A.5.5 0 0 0 11 3.503v-.006a.5.5 0 0 0-.146-.35l-1.5-1.5a.5.5 0 1 0-.708.707L9.293 3zM3 2h1.256q.19-.535.502-1H3a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2v1.5a.5.5 0 0 0 .777.416L6.651 9H9a2 2 0 0 0 1.984-1.747a4.5 4.5 0 0 1-1.557.651A1 1 0 0 1 9 8H6.5a.5.5 0 0 0-.277.084L4 9.566V8.5a.5.5 0 0 0-.5-.5H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

</style>
