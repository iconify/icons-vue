<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2hc6zogv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bottom-panel-open-outline" /></template>
<style>
.p2hc6zogv {
  fill: currentColor;
  d: path("M8 11.5h8l-4-4zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-5v3h14v-3zm0-2h14V5H5zm0 2v3z");
}

</style>
