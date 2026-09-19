<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wv1_azz2h"/><path class="fkfee6u6j"/><path class="hm9auybln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iriunwebcam" /></template>
<style>
.fkfee6u6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.396 36.486A11.417 11.417 0 1 0 13.979 25.07a11.43 11.43 0 0 0 11.417 11.417M24 4.5a17.219 17.219 0 1 0 17.219 17.219A17.22 17.22 0 0 0 24 4.5");
}

.hm9auybln {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.81 37.537a38.8 38.8 0 0 1 6.883 5.346a3.3 3.3 0 0 1-.558.45a50 50 0 0 0-12.464-1.4a53.8 53.8 0 0 0-13.39 1.567a15 15 0 0 1-.98-.637c1.045-1.055 5.852-4.848 7.102-5.236");
}

.wv1_azz2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.464 33.868a8.687 8.687 0 1 1 8.687-8.687a8.696 8.696 0 0 1-8.687 8.687");
}

</style>
