<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ho1u_tpyn"/><path class="me9sw-gog"/><path class="b5_zjfbre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:groupalarm" /></template>
<style>
.b5_zjfbre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.472 16.297a8.525 8.525 0 1 1 5.356 16.188M15.04 22.474a4.77 4.77 0 1 0-9.54 0v4.86a4.77 4.77 0 1 0 9.54 0h-4.77m15.316-.224h-6.103m-1.654 4.993l4.77-14.399l4.769 14.399");
}

.ho1u_tpyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.33 9.821c8.046-2.662 16.727 1.703 19.389 9.749s-1.702 16.727-9.748 19.39");
}

.me9sw-gog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.4 13.059c6.259-2.07 13.01 1.324 15.081 7.582s-1.324 13.01-7.582 15.081");
}

</style>
