<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0x3h3b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:center-focus-weak-outline" /></template>
<style>
.k0x3h3b8h {
  fill: currentColor;
  d: path("M9.175 14.825Q8 13.65 8 12t1.175-2.825T12 8t2.825 1.175T16 12t-1.175 2.825T12 16t-2.825-1.175m4.238-1.412Q14 12.825 14 12t-.587-1.412T12 10t-1.412.588T10 12t.588 1.413T12 14t1.413-.587M5 21q-.825 0-1.412-.587T3 19v-4h2v4h4v2zm10 0v-2h4v-4h2v4q0 .825-.587 1.413T19 21zM3 9V5q0-.825.588-1.412T5 3h4v2H5v4zm16 0V5h-4V3h4q.825 0 1.413.588T21 5v4z");
}

</style>
