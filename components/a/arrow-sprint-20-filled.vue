<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rzd4nnidj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-sprint-20-filled" /></template>
<style>
.rzd4nnidj {
  fill: currentColor;
  d: path("M10 6.5a3 3 0 1 0 0 6h6.44l-.72-.72a.75.75 0 1 1 1.06-1.06l2 2a.75.75 0 0 1 0 1.06l-2 2a.75.75 0 1 1-1.06-1.06l.72-.72H10a4.5 4.5 0 1 1 4.032-2.5h-1.796A3 3 0 0 0 10 6.5m-7.25 6h2.64A5.5 5.5 0 0 0 6.836 14H2.75a.75.75 0 0 1 0-1.5");
}

</style>
