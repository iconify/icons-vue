<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpvss8lpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-full-fill-round" /></template>
<style>
.tpvss8lpt {
  fill: currentColor;
  d: path("M6 6h9a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4m1 4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm3 4v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m3-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm3 4v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m6-4v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
