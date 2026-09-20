<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9xtdkb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-5-outline" /></template>
<style>
.a9xtdkb-w {
  fill: currentColor;
  d: path("M9 17h4q.825 0 1.413-.587T15 15v-2q0-.825-.587-1.412T13 11h-2V9h4V7H9v6h4v2H9zm-4 4q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
