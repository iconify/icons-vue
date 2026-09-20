<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yqn5uccup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:item-compare-20-filled" /></template>
<style>
.yqn5uccup {
  fill: currentColor;
  d: path("M10 2a.5.5 0 0 1 .5.5v15l-.01.1a.5.5 0 0 1-.98 0l-.01-.1v-15A.5.5 0 0 1 10 2M6 6.5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2zm11 0a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2z");
}

</style>
