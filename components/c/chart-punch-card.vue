<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpllixbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chart-punch-card" /></template>
<style>
.wpllixbyw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75Q8.75 1.75 8.75 5T12 8.25T15.25 5T12 1.75M16.5 5q0-2.5 2.5-2.5T21.5 5T19 7.5T16.5 5M3.25 5q0-1.75 1.75-1.75T6.75 5T5 6.75T3.25 5M5 8.75q-3.25 0-3.25 3.25T5 15.25T8.25 12T5 8.75m14 0q-3.25 0-3.25 3.25T19 15.25T22.25 12T19 8.75M10.25 12q0-1.75 1.75-1.75T13.75 12T12 13.75T10.25 12M2.5 19q0-2.5 2.5-2.5T7.5 19T5 21.5T2.5 19m9.5-2.5q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T14.5 19t-.732-1.768T12 16.5m5.25 2.5q0-1.75 1.75-1.75T20.75 19T19 20.75T17.25 19");
}

</style>
