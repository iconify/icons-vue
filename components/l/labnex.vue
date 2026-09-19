<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i0xpxnzlv"/><circle class="i5kqru1go"/><circle class="fcp2k0wsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:labnex" /></template>
<style>
.fcp2k0wsl {
  cx: 30.801px;
  cy: 29.664px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i0xpxnzlv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 42.5l18.5-14.586L36.312 5.5l-6.136 14.478H17.824L11.688 5.5L5.5 27.914z");
}

.i5kqru1go {
  cx: 17.199px;
  cy: 29.664px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
