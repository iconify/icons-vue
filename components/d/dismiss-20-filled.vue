<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x5aycrnpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-20-filled" /></template>
<style>
.x5aycrnpo {
  fill: currentColor;
  d: path("m3.897 4.054l.073-.084a.75.75 0 0 1 .976-.073l.084.073L10 8.939l4.97-4.97a.75.75 0 0 1 .976-.072l.084.073a.75.75 0 0 1 .073.976l-.073.084L11.061 10l4.97 4.97a.75.75 0 0 1 .072.976l-.073.084a.75.75 0 0 1-.976.073l-.084-.073L10 11.061l-4.97 4.97a.75.75 0 0 1-.976.072l-.084-.073a.75.75 0 0 1-.073-.976l.073-.084L8.939 10l-4.97-4.97a.75.75 0 0 1-.072-.976l.073-.084z");
}

</style>
