<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5wa_kd_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-8" /></template>
<style>
.f5wa_kd_w {
  fill: currentColor;
  d: path("M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5h14v14H5zm6 12h2q.825 0 1.413-.587T15 15v-1.5q0-.625-.437-1.062T13.5 12q.625 0 1.063-.437T15 10.5V9q0-.825-.587-1.412T13 7h-2q-.825 0-1.412.588T9 9v1.5q0 .625.438 1.063T10.5 12q-.625 0-1.062.438T9 13.5V15q0 .825.588 1.413T11 17m0-8h2v2h-2zm0 6v-2h2v2z");
}

</style>
