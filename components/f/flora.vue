<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="me1gh5b-d"/><circle class="j0ewg9bxq"/><path class="lf_93obsd"/><path class="ys4osvb7m"/><path class="wdb7kpbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flora" /></template>
<style>
.j0ewg9bxq {
  cx: 24.002px;
  cy: 24px;
  r: 4.543px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lf_93obsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.005 36.131c-.954 3.962-4.286 8.369-7.003 8.369c-2.713 0-6.039-4.394-6.998-8.351M17 11.869c.954-3.962 4.285-8.369 7.002-8.369c2.714 0 6.04 4.394 6.999 8.352");
}

.me1gh5b-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 11.869c.954-3.962 4.285-8.369 7.002-8.369c2.714 0 6.04 4.394 6.999 8.352");
}

.wdb7kpbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.01 24.001c2.954 2.807 5.105 7.896 3.746 10.249c-1.357 2.35-6.825 3.033-10.732 1.885m-14.031-.002c-3.908 1.154-9.39.473-10.749-1.88c-1.356-2.35.786-7.427 3.734-10.237");
}

.ys4osvb7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.74 11.322c-2.87.04-5.59.866-6.491 2.428c-1.605 2.778 1.681 9.365 5.406 11.516a13.53 13.53 0 0 0 8.06 1.21a13.53 13.53 0 0 0-2.982 7.584c0 4.3 4.062 10.44 7.27 10.44s7.27-6.14 7.27-10.44a13.53 13.53 0 0 0-2.981-7.582a13.54 13.54 0 0 0 8.054-1.21c3.725-2.15 7.009-8.738 5.405-11.515s-8.952-3.226-12.676-1.076A13.53 13.53 0 0 0 24 19.046a13.53 13.53 0 0 0-5.076-6.371a12.6 12.6 0 0 0-6.184-1.353");
}

</style>
