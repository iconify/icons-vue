<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hc1jheewz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-down-20-regular" /></template>
<style>
.hc1jheewz {
  fill: currentColor;
  d: path("M16.854 11.146a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 .708-.708L12 14.293V8a2 2 0 0 0-2-2H3.5a.5.5 0 0 1 0-1H10a3 3 0 0 1 3 3v6.293l3.146-3.147a.5.5 0 0 1 .708 0");
}

</style>
