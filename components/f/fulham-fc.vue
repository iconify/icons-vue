<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qu_gecbfb"/><path class="sjewvri4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fulham-fc" /></template>
<style>
.qu_gecbfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.352 4.978V37.63M24 43.49s14.7-7.091 14.7-16.414V6.328S34.695 4.49 24 4.49S9.3 6.328 9.3 6.328v20.748C9.3 36.399 24 43.49 24 43.49m8.648-38.512V37.63");
}

.sjewvri4e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.738 35.941l-.034.034a3.9 3.9 0 0 1-5.517 0h0a3.9 3.9 0 0 1 0-5.516l2.811-2.81a3.9 3.9 0 0 1 5.517 0h0a3.9 3.9 0 0 1 0 5.516l-.034.034m-5.208-18.403l3.382 3.382m-7.545.782l8.327-8.327l4.164 4.163m-9.109 7.546l4.163 4.164m-8.327 0l8.327-8.328l4.164 4.164");
}

</style>
