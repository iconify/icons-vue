<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlp94i-tq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:castle-rounded" /></template>
<style>
.jlp94i-tq {
  fill: currentColor;
  d: path("M1 19v-9q0-.425.288-.712T2 9t.713.288T3 10v1h2V4q0-.425.288-.712T6 3t.713.288T7 4v1h2V4q0-.425.288-.712T10 3t.713.288T11 4v1h2V4q0-.425.288-.712T14 3t.713.288T15 4v1h2V4q0-.425.288-.712T18 3t.713.288T19 4v7h2v-1q0-.425.288-.712T22 9t.713.288T23 10v9q0 .825-.587 1.413T21 21h-6q-.425 0-.712-.288T14 20v-2q0-.825-.587-1.412T12 16t-1.412.588T10 18v2q0 .425-.288.713T9 21H3q-.825 0-1.412-.587T1 19m8.25-7h1.5q.125 0 .188-.062T11 11.75V10q0-.425-.288-.712T10 9t-.712.288T9 10v1.75q0 .125.063.188T9.25 12m4 0h1.5q.125 0 .188-.062T15 11.75V10q0-.425-.288-.712T14 9t-.712.288T13 10v1.75q0 .125.063.188t.187.062");
}

</style>
