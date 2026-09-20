<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vtvyp2-6h"/><path class="k5il-rbpc"/><path class="qa-_p0i8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jira" /></template>
<style>
.k5il-rbpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.236 14.236za8.736 8.736 0 0 0 8.736 8.736h2.056v2.056a8.736 8.736 0 0 0 8.736 8.736V14.236Z");
}

.qa-_p0i8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.972 5.5za8.736 8.736 0 0 0 8.736 8.736h2.056v2.056a8.736 8.736 0 0 0 8.736 8.736V5.5Z");
}

.vtvyp2-6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 22.972za8.736 8.736 0 0 0 8.736 8.736h2.056v2.056a8.736 8.736 0 0 0 8.736 8.736V22.972Z");
}

</style>
