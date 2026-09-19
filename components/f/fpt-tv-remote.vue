<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="nmmi1bnjz"/><circle class="t1rmvy4mn"/><path class="j2d41gbsc"/><path class="em73p04lg"/></g><path class="l47o4jaix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fpt-tv-remote" /></template>
<style>
.em73p04lg {
  d: path("M10.751 26.037V15.382A9.86 9.86 0 0 1 20.633 5.5h11.86a9.86 9.86 0 0 1 9.881 9.882v11.859a9.86 9.86 0 0 1-9.882 9.882H21.907");
}

.j2d41gbsc {
  d: path("M24.586 20.323a2.965 2.965 0 0 1 2.965 2.965m-2.718-4.694a4.447 4.447 0 0 1 4.447 4.447M5.626 31.194l9.218-9.219a3.944 3.944 0 0 1 5.59 0l5.59 5.59a3.944 3.944 0 0 1 0 5.591L16.682 42.5");
}

.l47o4jaix {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.645 26.747l1.398 1.397");
}

.nmmi1bnjz {
  cx: 14.21px;
  cy: 33.664px;
  r: 5.435px;
}

.t1rmvy4mn {
  cx: 14.21px;
  cy: 33.664px;
  r: 2.471px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
