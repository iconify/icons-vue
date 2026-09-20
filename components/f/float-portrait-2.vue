<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unwopb31b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:float-portrait-2" /></template>
<style>
.unwopb31b {
  fill: currentColor;
  d: path("M8 11h6V6H8zm12 9q0 .825-.587 1.413T18 22H6q-.825 0-1.412-.587T4 20V4q0-.825.588-1.412T6 2h12q.825 0 1.413.588T20 4z");
}

</style>
