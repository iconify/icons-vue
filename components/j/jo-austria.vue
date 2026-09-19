<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qapf9eb8w"/><circle class="q9wlpi3id"/><circle class="hst9t5b1w"/><circle class="n553sm6_q"/><circle class="c_7jaf1ac"/><path class="sjdysrurz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jo-austria" /></template>
<style>
.c_7jaf1ac {
  cx: 17.819px;
  cy: 14.311px;
  r: 2.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hst9t5b1w {
  cx: 32.431px;
  cy: 14.311px;
  r: 2.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n553sm6_q {
  cx: 25.614px;
  cy: 14.311px;
  r: 2.532px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q9wlpi3id {
  cx: 29.023px;
  cy: 25.032px;
  r: 6.699px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qapf9eb8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.66 42.67c-.08.05-.17.1-.26.15A21.4 21.4 0 0 1 24 45.5C12.13 45.5 2.5 35.87 2.5 24S12.13 2.5 24 2.5S45.5 12.13 45.5 24c0 3.95-1.06 7.65-2.92 10.83l.55 8.52z");
}

.sjdysrurz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.082 18.558h5.157v13.377c.023.236.158 1.859-1.067 3.122c-.996 1.027-1.991 1.164-2.546 1.164h-4.347l.434-5.017c.585.517 1.327.647 1.832.349c.26-.153.484-.379.484-.982zm13.941 8.333c1.402 0 2.095-.304 3.627-1.859c.09 1.95-.975 4.086-3.627 4.086s-3.718-2.135-3.628-4.086c1.533 1.555 2.225 1.86 3.628 1.86");
}

</style>
