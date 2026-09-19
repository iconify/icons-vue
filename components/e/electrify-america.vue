<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg5lro6gw"/><path class="o33imhbrn"/><path class="xfexudb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:electrify-america" /></template>
<style>
.o33imhbrn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.602 29.056c.81.43 1.866.668 3.187.669c3.639.002 5.73-2.784 5.73-2.784m.375-9.107c-2.443-2.958-9.216-.826-10.872 4.288c-.973 3.003-.665 5.51 1.275 6.756");
}

.xfexudb_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.902 22.805c7.18.978 12.51-.302 11.72-3.519");
}

.xg5lro6gw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.223 7.109l11.982-2.733l-4.875 15.217l7.29-1.731l-19.956 25.514l4.01-14.58l-5.468 1.185z");
}

</style>
