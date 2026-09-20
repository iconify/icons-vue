<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm55tibdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-arrow-right-outline" /></template>
<style>
.qm55tibdy {
  fill: currentColor;
  d: path("M9 13L3.225 5.625q-.125-.15-.175-.312T3 5q0-.4.288-.7T4 4h14q.425 0 .713.3T19 5q0 .15-.05.313t-.175.312L13 13v6q0 .425-.288.713T12 20h-2q-.425 0-.712-.288T9 19zm10 6l-1.4-1.4l1.575-1.6H15v-2h4.175L17.6 12.4L19 11l4 4zm-8-6.7L15.95 6h-9.9z");
}

</style>
