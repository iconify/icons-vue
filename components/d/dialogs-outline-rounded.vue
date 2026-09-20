<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfk-q741q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dialogs-outline-rounded" /></template>
<style>
.sfk-q741q {
  fill: currentColor;
  d: path("M9 16h6q.425 0 .713-.288T16 15V9q0-.425-.288-.712T15 8H9q-.425 0-.712.288T8 9v6q0 .425.288.713T9 16m-4 5q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
