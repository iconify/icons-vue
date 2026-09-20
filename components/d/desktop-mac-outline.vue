<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg8iwsk9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-mac-outline" /></template>
<style>
.pg8iwsk9v {
  fill: currentColor;
  d: path("M8 21v-1l2-2H4q-.825 0-1.412-.587T2 16V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v11q0 .825-.587 1.413T20 18h-6l2 2v1zm-4-8h16V5H4zm0 0V5z");
}

</style>
