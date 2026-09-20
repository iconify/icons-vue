<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e6dxln4yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-add-20-regular" /></template>
<style>
.e6dxln4yz {
  fill: currentColor;
  d: path("M12.5 15a.5.5 0 0 1 .09.992L12.5 16h-5a.5.5 0 0 1-.09-.992L7.5 15zm2-4a.5.5 0 0 1 .09.992L14.5 12h-9a.5.5 0 0 1-.09-.992L5.5 11zm0-10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M9.208 7q.149.524.394 1H3.5a.5.5 0 0 1-.09-.992L3.5 7zM14.5 3a.5.5 0 0 0-.5.5V5h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V6h1.5a.5.5 0 0 0 0-1H15V3.5a.5.5 0 0 0-.5-.5");
}

</style>
