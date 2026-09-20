<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcn6sgbrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:light-off" /></template>
<style>
.jcn6sgbrv {
  fill: currentColor;
  d: path("M10.588 21.413Q10 20.825 10 20h4q0 .825-.587 1.413T12 22t-1.412-.587M17.45 14.6L6.85 4.05q1.025-.95 2.338-1.5T12 2q3.125 0 5.313 2.188T19.5 9.5q0 1.775-.625 3.038T17.45 14.6m3.75 6.6l-1.425 1.425L13.15 16h-4.9q-1.725-1.025-2.738-2.75T4.5 9.5q0-.5.063-.975T4.75 7.6L1.4 4.2l1.4-1.4zM16.15 17v2H8v-2z");
}

</style>
