<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dowec2btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-bidirectional-down-right-20-regular" /></template>
<style>
.dowec2btx {
  fill: currentColor;
  d: path("M13.854 2.146a.5.5 0 0 0-.708.708L16.293 6H9a3 3 0 0 0-3 3v7.293l-3.146-3.147a.5.5 0 0 0-.708.708l4 4a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0-.708-.708L7 16.293V9a2 2 0 0 1 2-2h7.293l-3.147 3.146a.5.5 0 0 0 .708.708l4-4a.5.5 0 0 0 0-.708z");
}

</style>
