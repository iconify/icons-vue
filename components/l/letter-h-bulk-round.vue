<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-d78hkpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:letter-h-bulk-round" /></template>
<style>
.y-d78hkpq {
  fill: currentColor;
  d: path("M8 11h8V4a1 1 0 0 1 2 0v16a1 1 0 0 1-2 0v-7H8v7a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0Z");
}

</style>
