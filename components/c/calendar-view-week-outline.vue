<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_k2tqeta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-view-week-outline" /></template>
<style>
.x_k2tqeta {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm9-2h2.5V6H13zm-4.5 0H11V6H8.5zM4 18h2.5V6H4zm13.5 0H20V6h-2.5z");
}

</style>
