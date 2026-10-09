<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfoga5bay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-9-outline" /></template>
<style>
.nfoga5bay {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14zm5 12h3q.825 0 1.413-.587T15 15V9q0-.825-.587-1.412T13 7h-2q-.825 0-1.412.588T9 9v2q0 .825.588 1.413T11 13h2v2h-3zm3-6h-2V9h2z");
}

</style>
