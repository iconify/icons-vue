<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6j9kxb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-5-fill-round" /></template>
<style>
.t6j9kxb1y {
  fill: currentColor;
  d: path("M4 5v6h6V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0v-6H4v6a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m17 5h-5v2h2a4 4 0 0 1 0 8h-3a1 1 0 0 1 0-2h3a2 2 0 1 0 0-4h-3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1h6a1 1 0 0 1 0 2");
}

</style>
