<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="w68_5r_vw"/><path class="tn9jugxpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:consentid" /></template>
<style>
.tn9jugxpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.146 25.71l4.952-2.917l1.905 3.234l-4.952 2.918zm22.354 11c-4.185-2.024-8.836-3.426-13.09-4.37m-7.755 2.755c-6.735 3.493-16.155 5.011-16.155 0s7.29-4.526 10.647-4.526c.652 0 1.664.05 2.939.156");
}

.w68_5r_vw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.72 19.406L34.213 9.69l6.348 10.776a4.575 4.575 0 0 1-1.62 6.26l-16.49 9.716l-6.348-10.776a4.575 4.575 0 0 1 1.619-6.26");
}

</style>
