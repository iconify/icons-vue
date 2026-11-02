<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8vghd45x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-z-bulk" /></template>
<style>
.r8vghd45x {
  fill: currentColor;
  d: path("M17 3a1 1 0 0 1 .848 1.53L8.804 19H17a1 1 0 0 1 0 2H7a1 1 0 0 1-.848-1.53L15.196 5H7a1 1 0 0 1 0-2Z");
}

</style>
