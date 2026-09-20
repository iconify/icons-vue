<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljq7vnb4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-road" /></template>
<style>
.ljq7vnb4w {
  fill: currentColor;
  d: path("M16 12.125V4h2v6.125zM4 20V4h2v16zm6-12V4h2v4zm0 6v-4h2v4zm0 6v-4h2v4zm4 0v-3.075l5.525-5.5q.225-.225.5-.325t.55-.1q.3 0 .575.113t.5.337l.925.925q.2.225.313.5t.112.55t-.1.563t-.325.512l-5.5 5.5zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
