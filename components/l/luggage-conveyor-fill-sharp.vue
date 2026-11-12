<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-qbq4bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-conveyor-fill-sharp" /></template>
<style>
.t-qbq4bsp {
  fill: currentColor;
  d: path("M8 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v3h2a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h2Zm6 3V4h-4v2ZM9 9v2a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0m4 0v2a1 1 0 0 0 2 0V9a1 1 0 0 0-2 0M2 17a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm2 1v2h16v-2Z");
}

</style>
