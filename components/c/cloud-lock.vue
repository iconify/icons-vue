<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdxp8xb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cloud-lock" /></template>
<style>
.jdxp8xb-s {
  fill: currentColor;
  d: path("M6.5 20q-2.275 0-3.887-1.575T1 14.575q0-1.95 1.175-3.475T5.25 9.15q.625-2.3 2.5-3.725T12 4q2.65 0 4.613 1.713T18.925 10q-2.05.05-3.488 1.488T14 15v5zM17 20q-.425 0-.712-.288T16 19v-3q0-.425.288-.712T17 15v-1q0-.825.588-1.412T19 12t1.413.588T21 14v1q.425 0 .713.288T22 16v3q0 .425-.288.713T21 20zm1-5h2v-1q0-.425-.288-.712T19 13t-.712.288T18 14z");
}

</style>
