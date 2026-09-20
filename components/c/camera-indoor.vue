<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy8tqgj9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:camera-indoor" /></template>
<style>
.oy8tqgj9r {
  fill: currentColor;
  d: path("M4 21V9l8-6l8 6v12zm5-4h4q.425 0 .713-.288T14 16v-1l2 1.05v-4.1L14 13v-1q0-.425-.288-.712T13 11H9q-.425 0-.712.288T8 12v4q0 .425.288.713T9 17");
}

</style>
