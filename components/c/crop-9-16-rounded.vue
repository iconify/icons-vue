<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_tq-cb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-9-16-rounded" /></template>
<style>
.r_tq-cb-v {
  fill: currentColor;
  d: path("M9 21q-.825 0-1.412-.587T7 19V5q0-.825.588-1.412T9 3h6q.825 0 1.413.588T17 5v14q0 .825-.587 1.413T15 21z");
}

</style>
