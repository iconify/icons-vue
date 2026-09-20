<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kdn6kso_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-20-filled" /></template>
<style>
.kdn6kso_q {
  fill: currentColor;
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5V6h14v-.5A2.5 2.5 0 0 0 14.5 3zM17 7H3v7.5A2.5 2.5 0 0 0 5.5 17h9a2.5 2.5 0 0 0 2.5-2.5zm-9 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 4a1 1 0 1 1 0-2a1 1 0 0 1 0 2m4-4a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 4a1 1 0 1 1 0-2a1 1 0 0 1 0 2m4-4a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
