<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7tu1cbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-check" /></template>
<style>
.g7tu1cbrf {
  fill: currentColor;
  d: path("M5 22q-.825 0-1.412-.587T3 20V6q0-.825.588-1.412T5 4h1V2h2v2h8V2h2v2h1q.825 0 1.413.588T21 6v6.375l-2 2V10H5v10h6.2l2 2zm11.55.5L13 18.95l1.4-1.4l2.125 2.125l4.25-4.25l1.4 1.425z");
}

</style>
