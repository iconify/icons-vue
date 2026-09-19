<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="da13febst"/><circle class="xvd9fmguq"/><path class="mdh7z0b8q"/><circle class="l44pzonmx"/><path class="sics6hsby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cultist-simulator" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.da13febst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.989 20.279c1.89 3.012 4.489 1.358 7.088 5.198s-.236 6.91.945 9.096c-2.126-2.6-5.719-1.296-7.206-3.958c-2.244-4.016.945-6.704-.827-10.336");
}

.l44pzonmx {
  cx: 36.795px;
  cy: 27.788px;
  r: 1.706px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mdh7z0b8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.037 9.381c0 4.844 7.007 6.91 6.003 14.663s-6.003 7.162-6.003 13.364c0-6.202-4.999-5.611-6.003-13.364c-1.004-7.752 6.003-9.82 6.003-14.663m17.048 10.898c-1.89 3.012-4.49 1.358-7.088 5.198s.236 6.91-.945 9.096c2.126-2.6 5.718-1.296 7.206-3.958c2.244-4.016-.945-6.704.827-10.336");
}

.sics6hsby {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.074 28.718c2.444 0 3.44-2.658 3.44-4.674s-.841-5.36-3.477-5.36s-3.478 3.345-3.478 5.36s.997 4.674 3.441 4.674");
}

.xvd9fmguq {
  cx: 11.279px;
  cy: 27.788px;
  r: 1.706px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
