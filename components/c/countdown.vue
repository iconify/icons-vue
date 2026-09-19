<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4zjb1bcb"/><g class="y9tr6bcfx"><path class="rnwffsh9e"/><path class="z_r0ylbtp"/><path class="e1c35bcxx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:countdown" /></template>
<style>
.c4zjb1bcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.874 0 21.5 9.626 21.5 21.5S35.874 45.5 24 45.5S2.5 35.874 2.5 24m18 7h7m-7-12.094L24 17m0 0v14");
}

.e1c35bcxx {
  d: path("M22.5 2.552Q23.244 2.5 24 2.5");
}

.rnwffsh9e {
  d: path("M2.5 24q0-.756.052-1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_r0ylbtp {
  stroke-dasharray: 0 0 2.797 2.797;
  d: path("M2.925 19.728c1.794-8.902 9.087-15.812 18.183-17.035");
}

</style>
