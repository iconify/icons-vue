<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t0iq2_rrk"/><path class="l44r85kqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-star-and-crescent" /></template>
<style>
.l44r85kqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.832 18.003l1.756 3.557l3.927.57l-2.841 2.77l.67 3.91l-3.512-1.846l-3.512 1.846l.671-3.91l-2.841-2.77l3.927-.57z");
}

.t0iq2_rrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.65 39.54c1.461 0 2.886-.203 4.227-.592A18.35 18.35 0 0 1 24.988 42.5C14.765 42.5 6.485 34.221 6.485 24s8.28-18.5 18.503-18.5c4.07 0 7.836 1.314 10.89 3.552a15.2 15.2 0 0 0-4.229-.592c-8.585 0-15.542 6.956-15.542 15.54s6.957 15.54 15.542 15.54");
}

</style>
