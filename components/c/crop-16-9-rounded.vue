<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbahlpcgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-16-9-rounded" /></template>
<style>
.wbahlpcgc {
  fill: currentColor;
  d: path("M5 17q-.825 0-1.412-.587T3 15V9q0-.825.588-1.412T5 7h14q.825 0 1.413.588T21 9v6q0 .825-.587 1.413T19 17z");
}

</style>
