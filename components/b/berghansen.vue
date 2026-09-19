<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yaigqc7sw"/><path class="r--ddfq8z"/><path class="v6hynkbjc"/><path class="egd59tb2y"/><path class="rsgs1jbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:berghansen" /></template>
<style>
.egd59tb2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.876 0 21.5 9.624 21.5 21.5S35.876 45.5 24 45.5S2.5 35.876 2.5 24S12.124 2.5 24 2.5");
}

.r--ddfq8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.467 36.845a47 47 0 0 0 3.72 2.374m-1.745-32c-15.628-3.076-18.05 6.837-16.038 13.62c1.521 5.127 7.204 10.902 12.685 15.005");
}

.rsgs1jbzv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.67 23.775c3.277.114 6.213 1.152 8.535 3.473c5.575 5.575 2.036 12.369-.062 17.037M3.343 29.98c3.524-1.982 7.191-3.703 10.748-4.828");
}

.v6hynkbjc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.376 45.236C16.634 36.863 13.354 30.64 14.062 19.571S25.001 3.343 34.196 5.066");
}

.yaigqc7sw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.027 14.327c8.714.746 15.246 5.705 15.246 15.158c0 5.71-1.374 10.368-3.095 13.964M3.441 17.688c3.936-1.754 7.953-2.849 11.766-3.267");
}

</style>
