<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sedbeo77u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chess-bishop-2-sharp" /></template>
<style>
.sedbeo77u {
  fill: currentColor;
  d: path("M6 18q-1.025-1.275-1.513-2.95T4 11.175q0-1.85 1.625-3.738t4.6-3.537q-.125-.2-.175-.437T10 3q0-.825.588-1.412T12 1t1.413.588T14 3q0 .2-.05.413t-.15.412q3.125 1.65 4.662 3.488T20 11.175q0 2.425-.462 4.025T18 18zm-2 4v-3h16v3zm7-8h2v-2h2v-2h-2V8h-2v2H9v2h2z");
}

</style>
