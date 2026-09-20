<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksagr5p6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:breaking-news-alt-1-outline" /></template>
<style>
.ksagr5p6u {
  fill: currentColor;
  d: path("M6 17h5v-2H6zm10 0h2v-2h-2zM6 13h5v-2H6zm10 0h2V7h-2zM6 9h5V7H6zM4 21q-.825 0-1.412-.587T2 19V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v14q0 .825-.587 1.413T20 21zm0-2h16V5H4zm0 0V5z");
}

</style>
