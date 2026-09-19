<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="umfirvbyf"/><ellipse class="ao3h8ofvm"/><path class="p7fpg-zyu"/><path class="ybas3v0pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:indiamart" /></template>
<style>
.ao3h8ofvm {
  cx: 29.287px;
  cy: 9.414px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.344px;
  ry: 4.273px;
}

.p7fpg-zyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.854 19.322c-1.667 2.224-1.926 3.73-1.635 6.31c.292 2.58 1.147 6.149 5.246 9.794s11.44 7.368 18.667 7.432s14.337-3.53 15.557-8.741s-3.453-12.04-9.524-16c-6.072-3.96-13.253-5.01-18.635-4.21c-5.381.8-8.009 3.19-9.676 5.415");
}

.umfirvbyf {
  cx: 13.615px;
  cy: 9.941px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.322px;
  ry: 2.787px;
}

.ybas3v0pv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.1 37.467c.3-5.712.6-11.424.787-14.883c.188-3.46.265-4.666 1.382-2.933s3.273 6.405 5.43 11.077m1.684.115c2.199-4.043 4.397-8.086 5.823-10.268s2.081-2.503 2.954 1.43s1.963 12.116 3.053 20.3");
}

</style>
