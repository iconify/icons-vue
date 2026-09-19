<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i2fb-cbxm"/><circle class="benq3vack"/><circle class="qkt72j9ht"/><circle class="g5tq8nqbh"/><circle class="qoy5xp_yn"/><circle class="c78ndmbah"/><path class="ytikmbn2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cuscon" /></template>
<style>
.benq3vack {
  cx: 24.07px;
  cy: 11.138px;
  r: 4.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c78ndmbah {
  cx: 32.16px;
  cy: 36.862px;
  r: 4.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g5tq8nqbh {
  cx: 37.695px;
  cy: 20.749px;
  r: 4.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i2fb-cbxm {
  cx: 24.07px;
  cy: 25.36px;
  r: 5.438px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qkt72j9ht {
  cx: 10.305px;
  cy: 20.749px;
  r: 4.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qoy5xp_yn {
  cx: 15.415px;
  cy: 36.862px;
  r: 4.805px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ytikmbn2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.893 16.3a14.83 14.83 0 0 0-7.016-5.053m-9.461 28.27c1.463.49 3.028.746 4.654.746a14.6 14.6 0 0 0 4.193-.603M9.168 25.412a14.8 14.8 0 0 0 2.587 8.336m24.353.389v-.01a14.73 14.73 0 0 0 2.864-8.745M19.263 11.247a14.93 14.93 0 0 0-7.047 5.093m8.661 13.419l-2.553 3.284m14.834-10.715l-3.946 1.268m-5.142-7.653l.197 3.984");
}

</style>
