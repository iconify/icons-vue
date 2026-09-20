<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yencp7iad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:blur-20-filled" /></template>
<style>
.yencp7iad {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 0 5.292 14H10v-1h6.245q.38-.473.685-1H10v-1h7.419a8 8 0 0 0 .329-1H10v-1h7.938q.062-.492.062-1h-8V9h7.938a8 8 0 0 0-.19-1H10V7h7.419a8 8 0 0 0-.49-1H10V5h6.245a8 8 0 0 0-.953-1H10V3h3.876A7.96 7.96 0 0 0 10 2");
}

</style>
