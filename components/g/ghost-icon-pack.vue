<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jbb1jllyl"/><rect class="zn0r6un5g"/><rect class="ly_9apz1e"/><path class="b8e5akbjw"/><path class="bjutyzbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ghost-icon-pack" /></template>
<style>
.b8e5akbjw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 27.883a8.2 8.2 0 0 1-5.245-1.887c-1.173-.97-2.995-.163-2.996 1.36q-.002.781.15 1.592c.611 3.251 3.22 5.881 6.471 6.5c5.263 1.002 9.861-3.006 9.861-8.087v-.042c-.007-1.506-1.833-2.286-2.993-1.325A8.2 8.2 0 0 1 24 27.884Z");
}

.bjutyzbpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.243 32.096c2.604-1.415 8.19.186 9.514 3.033m1.105-8.208v2.171");
}

.jbb1jllyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.6 37.506a5.994 5.994 0 0 1-5.994 5.994c-1.975 0-3.711-.967-4.803-2.44C27.71 42.534 25.974 43.5 24 43.5s-3.71-.967-4.803-2.44c-1.092 1.473-2.828 2.44-4.802 2.44A5.994 5.994 0 0 1 8.4 37.506V20.1c0-8.616 6.985-15.6 15.6-15.6s15.6 6.984 15.6 15.6z");
}

.ly_9apz1e {
  width: 4.952px;
  height: 7.131px;
  x: 28.003px;
  y: 15.581px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.476px;
  ry: 2.476px;
}

.zn0r6un5g {
  width: 4.952px;
  height: 7.131px;
  x: 15.044px;
  y: 15.581px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.476px;
  ry: 2.476px;
}

</style>
