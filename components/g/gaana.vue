<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v2aje2fhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gaana" /></template>
<style>
.v2aje2fhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.573 43.5c9.669-.879 16.701 3.083 18.46-9.67l4.394-29.007C27.071 4.389 20.484 3.51 19.16 9.218l-2.637 15.389c-1.312 6.153 6.154 5.708 14.944 5.708");
}

</style>
