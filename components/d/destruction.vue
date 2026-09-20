<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnjb6_vry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:destruction" /></template>
<style>
.mnjb6_vry {
  fill: currentColor;
  d: path("M5 22q-.825 0-1.412-.587T3 20v-4q0-.825.588-1.412T5 14h14q.825 0 1.413.588T21 16v4q0 .825-.587 1.413T19 22zm1.525-9.5L1.5 9.65l6-1l-1.625-5.875L10.85 6.3l3-5.3l1 6l5.875-1.625L17.2 10.35L21 12.5z");
}

</style>
