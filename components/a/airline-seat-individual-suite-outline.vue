<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dj2lrwbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-individual-suite-outline" /></template>
<style>
.dj2lrwbjy {
  fill: currentColor;
  d: path("M1 17V7h2v8h8V7h8q1.65 0 2.825 1.175T23 11v6zm12-2h8v-4q0-.825-.587-1.412T19 9h-6zm0-6v6zm-3.875 4.125Q10 12.25 10 11t-.875-2.125T7 8t-2.125.875T4 11t.875 2.125T7 14t2.125-.875m-2.838-1.412Q6 11.425 6 11t.288-.712T7 10t.713.288T8 11t-.288.713T7 12t-.712-.288M7 11");
}

</style>
