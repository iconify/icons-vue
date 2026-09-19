<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o_e36h6ja"/><path class="ayc6i0buc"/><path class="k4h8xykop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jenius" /></template>
<style>
.ayc6i0buc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.933 7.511c9.153 0 16.567 7.282 16.567 16.267c0 8.973-7.414 16.255-16.567 16.255s-16.579-7.282-16.579-16.255c0-8.985 7.426-16.267 16.58-16.267");
}

.k4h8xykop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.507 12.897c8.278 0 14.996 6.178 14.996 13.796S27.785 40.49 19.507 40.49C11.218 40.49 4.5 34.312 4.5 26.694s6.718-13.796 15.007-13.796");
}

.o_e36h6ja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.251 13.09c5.135 0 9.31 4.174 9.31 9.309c0 5.146-4.175 9.32-9.31 9.32c-5.146 0-9.32-4.174-9.32-9.32c0-5.135 4.174-9.31 9.32-9.31");
}

</style>
