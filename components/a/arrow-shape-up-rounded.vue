<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy-1fop9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-shape-up-rounded" /></template>
<style>
.oy-1fop9v {
  fill: currentColor;
  d: path("M8 20v-5H4.575q-.475 0-.675-.425t.1-.8l7.225-8.825q.3-.375.775-.375t.775.375L20 13.775q.3.375.1.8t-.675.425H16v5q0 .425-.288.713T15 21H9q-.425 0-.712-.288T8 20");
}

</style>
