<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znuxyibor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-on-outline" /></template>
<style>
.znuxyibor {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h3.325v-3.325H5zm5.325 0h3.35v-3.325h-3.35zm5.35 0H19v-3.325h-3.325zM5 13.675h3.325v-3.35H5zm5.325 0h3.35v-3.35h-3.35zm5.35 0H19v-3.35h-3.325zM5 8.325h3.325V5H5zm5.325 0h3.35V5h-3.35zm5.35 0H19V5h-3.325z");
}

</style>
