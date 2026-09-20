<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7ydwyw9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:avg-time-outline" /></template>
<style>
.a7ydwyw9s {
  fill: currentColor;
  d: path("M5.017 12.5H8q.14 0 .256.07t.183.21L10 15.867l3.562-7.085q.14-.287.448-.287q.307 0 .448.287l1.86 3.719h2.665q-.183-2.742-2.2-4.621T12 6T7.217 7.879t-2.2 4.621m11.766 5.621q2.017-1.879 2.2-4.621H16q-.14 0-.256-.07t-.183-.21L14 10.134l-3.561 7.103q-.141.287-.448.277t-.449-.296L7.682 13.5H5.018q.183 2.742 2.2 4.621T12 20t4.783-1.879m-7.895 2.253q-1.455-.626-2.546-1.716t-1.716-2.545T4 13h1q0 2.9 2.05 4.95T12 20t4.95-2.05T19 13h1q0 1.658-.626 3.113t-1.716 2.545t-2.546 1.716T12 21t-3.113-.626M4 13q0-1.658.626-3.113t1.716-2.545t2.546-1.716T12 5q1.454 0 2.812.52t2.492 1.469l1.092-1.093l.708.708l-1.092 1.092q.95 1.135 1.469 2.493T20 13h-1q0-2.9-2.05-4.95T12 6T7.05 8.05T5 13zM9.385 2.5v-1h5.23v1zM7.05 17.95Q5 15.9 5 13t2.05-4.95T12 6t4.95 2.05T19 13t-2.05 4.95T12 20t-4.95-2.05M12 13");
}

</style>
