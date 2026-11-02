<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6qu1ubgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-fill" /></template>
<style>
.m6qu1ubgh {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM8 8h8a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3m13 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
