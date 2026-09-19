<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bbfs80bim"/><path class="l2xg2cmek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citi-mobile" /></template>
<style>
.bbfs80bim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.569 21.281v15.052m9.568-19.599v17.04a2.683 2.683 0 0 0 2.84 2.84h.852m-6.532-15.052h5.964M15.008 33.783a5.5 5.5 0 0 1-4.828 2.84h0a5.697 5.697 0 0 1-5.68-5.68V27.25a5.697 5.697 0 0 1 5.68-5.68h0a5.5 5.5 0 0 1 4.828 2.84m25.734-2.952V36.51");
}

.l2xg2cmek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.758 17.414c1.632-1.632 5.838-6.036 12.867-6.036S41.877 15.79 43.5 17.414");
}

</style>
