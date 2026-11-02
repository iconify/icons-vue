<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndcj8zbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-horizontal-fill-round" /></template>
<style>
.ndcj8zbpr {
  fill: currentColor;
  d: path("M5 21a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm16 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM8 9a4 4 0 0 1 8 0v6a4 4 0 0 1-8 0Z");
}

</style>
