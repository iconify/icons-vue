<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nojghdcxp"/><path class="r_lpty4dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:free-tv" /></template>
<style>
.nojghdcxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.232 36.026a6.474 6.474 0 1 1-12.949 0a6.474 6.474 0 0 1 12.949 0m-10.673-2.218h3.46m-1.73 5.113v-5.113");
}

.r_lpty4dt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.957 33.808l-1.73 5.113l-1.73-5.113M7.768 42.5l13.946-27.972c2.47-4.955 9.051-11.01 16.852-8.4M10.754 18.12h20.193");
}

</style>
