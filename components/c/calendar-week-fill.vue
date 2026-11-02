<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkd74zb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-week-fill" /></template>
<style>
.zkd74zb8y {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 1 2 0v1h6V3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h1ZM5 19a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1v-9H5Zm3-5h8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2");
}

</style>
