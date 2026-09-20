<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keyt63b7y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-hospital-outline" /></template>
<style>
.keyt63b7y {
  fill: currentColor;
  d: path("M10.5 17h3v-3.5H17v-3h-3.5V7h-3v3.5H7v3h3.5zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
