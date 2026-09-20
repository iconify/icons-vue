<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km8fsvbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bia-sharp" /></template>
<style>
.km8fsvbyl {
  fill: currentColor;
  d: path("M7 9.5h4.17q-.287-.302-.44-.667T10.577 8q0-.275.052-.525T10.785 7H7zm11.658.212Q20 9.308 20 8t-1.343-1.711t-2.869-.404t-2.869.404Q11.577 6.692 11.577 8t1.342 1.712t2.87.404t2.869-.404M3 19V9.5h3V6h5.606q.754-.596 1.879-.856t2.304-.26q1.928 0 3.57.719Q21 6.321 21 8v11h-5.5v-3.5h-1V19h-3v-3.5h-1V19h-3v-3.5h-1V19z");
}

</style>
