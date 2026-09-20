<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zva9clb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:controller-gen-outline-rounded" /></template>
<style>
.zva9clb4h {
  fill: currentColor;
  d: path("M12 18q2.5 0 4.25-1.75T18 12t-1.75-4.25T12 6T7.75 7.75T6 12t1.75 4.25T12 18m0-2q-1.65 0-2.825-1.175T8 12t1.175-2.825T12 8t2.825 1.175T16 12t-1.175 2.825T12 16m-.7-3.3q.275.275.7.275t.7-.275l1.4-1.4q.275-.275.275-.7t-.275-.7t-.7-.275t-.7.275l-1.4 1.4q-.275.275-.275.7t.275.7M5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm0-2h14V5H5zM5 5v14z");
}

</style>
