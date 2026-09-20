<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fewp3ob-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:high-quality-off" /></template>
<style>
.fewp3ob-w {
  fill: currentColor;
  d: path("M18 15.15V10q0-.425-.288-.712T17 9h-3q-.425 0-.712.35t-.288.8l1.5 1.5V10.5h2v3.15zM6 15h1.5v-2h2v2H11v-4L9.5 9.5v2h-2V9H6zm15.75 3.9L6.85 4H20q.825 0 1.413.588T22 6v11.9q0 .275-.05.525t-.2.475M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4l11 11h-2.8L1.4 4.2l1.4-1.4l18.4 18.4l-1.4 1.4l-2.65-2.6z");
}

</style>
