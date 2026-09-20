<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eudnicjhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:license-rounded" /></template>
<style>
.eudnicjhm {
  fill: currentColor;
  d: path("M9.875 12.125Q9 11.25 9 10t.875-2.125T12 7t2.125.875T15 10t-.875 2.125T12 13t-2.125-.875M12 21l-4.675 1.55q-.5.175-.913-.125t-.412-.8v-6.35q-.95-1.05-1.475-2.4T4 10q0-3.35 2.325-5.675T12 2t5.675 2.325T20 10q0 1.525-.525 2.875T18 15.275v6.35q0 .5-.413.8t-.912.125zm4.25-6.75Q18 12.5 18 10t-1.75-4.25T12 4T7.75 5.75T6 10t1.75 4.25T12 16t4.25-1.75");
}

</style>
