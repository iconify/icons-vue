<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubv0g8btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-empty-fill-round" /></template>
<style>
.ubv0g8btz {
  fill: currentColor;
  d: path("M2 10a4 4 0 0 1 4-4h9a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4Zm20 4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
