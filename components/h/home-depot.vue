<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="m15ayqbhz"/><rect transform="rotate(-45 19.77 26.004)" class="lpfoh1baj"/><path class="fgivt301x"/><rect transform="rotate(-45 33.58 25.287)" class="iop-i15nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:home-depot" /></template>
<style>
.fgivt301x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.503 32.4l-4.036-4.036l1.321-1.32c.747-.748 1.96-.747 2.708.002s.75 1.961.003 2.708l-1.321 1.321m4.281-9.703l2.674-2.673m2.699 5.372l-4.036-4.036m-9.538 13.574l1.315-1.315m2.721 1.315l-2.018 2.018l-4.036-4.036l2.018-2.017M23.403 39.5l-4.036-4.036l.908-.908a2.497 2.497 0 0 1 3.532 0l.504.505a2.497 2.497 0 0 1 0 3.53z");
}

.iop-i15nb {
  width: 3.781px;
  height: 5.708px;
  x: 31.689px;
  y: 22.433px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.891px;
  ry: 1.891px;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lpfoh1baj {
  width: 5.552px;
  height: 8.381px;
  x: 16.994px;
  y: 21.814px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.776px;
  ry: 2.776px;
}

.m15ayqbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.578 19.068l2.674-2.674m2.699 5.373l-4.036-4.036m2.648-2.648l4.036 4.036m-1.362-6.71l4.036 4.036m-4.7.648l2.674-2.674m1.44-1.424l1.315-1.316m2.721 1.316l-2.018 2.018l-4.036-4.036l2.018-2.018m6.809 16.233l-5.92-5.92l8.889 2.963l-2.954-8.88l5.917 5.917M9.168 30.68l5.927 5.926m-2.001-9.852l5.926 5.926m-6.9.952l3.926-3.926m15.302-15.28l1.932-1.932m3.994 1.932l-2.963 2.963l-5.926-5.926L31.348 8.5");
}

</style>
