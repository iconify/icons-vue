<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8jmygb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:font-download" /></template>
<style>
.w8jmygb-r {
  fill: currentColor;
  d: path("M6.4 18h2.1l1.1-3.05h4.8L15.5 18h2.1L13.05 6h-2.1zm3.8-4.8l1.75-4.95h.1l1.75 4.95zM4 22q-.825 0-1.412-.587T2 20V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v16q0 .825-.587 1.413T20 22z");
}

</style>
