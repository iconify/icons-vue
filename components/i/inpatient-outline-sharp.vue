<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n086zkhet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:inpatient-outline-sharp" /></template>
<style>
.n086zkhet {
  fill: currentColor;
  d: path("M19.5 15.5L16 12l3.5-3.5l1.4 1.4l-1.075 1.1H23v2h-3.175l1.075 1.1zM2 22V2h13v20zm2-11.475q.45-.275.95-.4T6 10h5q.55 0 1.05.125t.95.4V4H4zm3.088-2.113Q6.5 7.825 6.5 7t.588-1.412T8.5 5t1.413.588T10.5 7t-.587 1.413T8.5 9t-1.412-.587M4 20h9v-6q0-.825-.587-1.412T11 12H6q-.825 0-1.412.588T4 14zm3.5-1h2v-2h2v-2h-2v-2h-2v2h-2v2h2zM4 20h9z");
}

</style>
