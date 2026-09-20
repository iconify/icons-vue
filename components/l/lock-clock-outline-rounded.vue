<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbas0ecvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:lock-clock-outline-rounded" /></template>
<style>
.sbas0ecvj {
  fill: currentColor;
  d: path("M9 8h6V6q0-1.25-.875-2.125T12 3t-2.125.875T9 6zM6 22q-.825 0-1.412-.587T4 20V10q0-.825.588-1.412T6 8h1V6q0-2.075 1.463-3.537T12 1t3.538 1.463T17 6v2h1q.825 0 1.413.588T20 10q0 .5-.312.75T19 11t-.687-.25T18 10H6v10h5q.425 0 .713.288T12 21t-.288.713T11 22zm8.463-.462Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M18.5 17.8v-2.3q0-.2-.15-.35T18 15t-.35.15t-.15.35v2.275q0 .2.075.388t.225.337l1.5 1.5q.15.15.35.15T20 20t.15-.35t-.15-.35zM6 10v10z");
}

</style>
