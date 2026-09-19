<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n6kms6twp"/><path class="bsxow3b5q"/><path class="it9501byb"/><path class="cjdmbvbck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hsbc-payme" /></template>
<style>
.bsxow3b5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.356 39.978V18.674c0-5.883 4.765-10.652 10.644-10.652s10.644 4.77 10.644 10.652S29.879 29.326 24 29.326H13.356");
}

.cjdmbvbck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.452 18.674A3.55 3.55 0 1 1 24 22.224h-3.548z");
}

.it9501byb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.904 18.674c0-3.922 3.177-7.101 7.096-7.101s7.096 3.179 7.096 7.101s-3.177 7.102-7.096 7.102h-7.096z");
}

.n6kms6twp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.904 32.877H24c7.838 0 14.192-6.359 14.192-14.203S31.838 4.471 24 4.471S9.808 10.83 9.808 18.674v21.304a3.55 3.55 0 0 0 3.548 3.55a3.55 3.55 0 0 0 3.548-3.55z");
}

</style>
