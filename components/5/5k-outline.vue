<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke1skrpfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:5k-outline" /></template>
<style>
.ke1skrpfk {
  fill: currentColor;
  d: path("M13 15h1.5v-2.25L16.25 15h1.825l-2.325-3l2.325-3H16.25l-1.75 2.25V9H13zm-6.5 0H10q.425 0 .713-.288T11 14v-1.5q0-.425-.288-.712T10 11.5H8v-1h3V9H6.5v3.5h3v1h-3zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
