<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="yo43fuw7d"/><circle class="uooq8gb5j"/><path class="szugnv6_q"/><path class="efor_ibpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:island-bargains" /></template>
<style>
.efor_ibpz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.236 30.13c-1.478 4.319-2.373 9.057-2.697 13.108m21.519-7.114c-1.432-4.85-7.095-5.993-11.049-4.907c-2.467 4.262-2.658 13.352-2.658 13.352");
}

.szugnv6_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.168 26.907c-3.981-2.16-9.673.42-11.747 4.822c-.926-10.486 6.925-14.523 13.71-8.495c-.477-3.954-2.215-7.935-7.094-8.243c2.748-1.458 10.963-.926 11.888 5.803c4.486-3.259 9.42-2.782 13.43 2.433c-5.523-3-10.177-.057-11.748 2.915c5.44-1.401 10.823.505 11.748 4.963");
}

.uooq8gb5j {
  cx: 30.346px;
  cy: 9.579px;
  r: 3.841px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yo43fuw7d {
  cx: 24px;
  cy: 23.069px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
