<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qgtgc0cdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-left-down-20-regular" /></template>
<style>
.qgtgc0cdc {
  fill: currentColor;
  d: path("M3.146 11.146a.5.5 0 0 0 0 .708l4 4a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0-.708-.708L8 14.293V8a2 2 0 0 1 2-2h6.5a.5.5 0 0 0 0-1H10a3 3 0 0 0-3 3v6.293l-3.146-3.147a.5.5 0 0 0-.708 0");
}

</style>
