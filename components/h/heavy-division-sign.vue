<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="mc-vbtb-v"><path class="o7-hbnjye"/><circle class="y6woiebfp"/><circle class="eo9d_lsqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:heavy-division-sign" /></template>
<style>
.eo9d_lsqc {
  cx: 32px;
  cy: 54.5px;
  r: 7.5px;
}

.mc-vbtb-v {
  fill: var(--svg-color--4d5357, #4d5357);
}

.o7-hbnjye {
  d: path("M2 26h60v12H2z");
}

.y6woiebfp {
  cx: 32px;
  cy: 9.5px;
  r: 7.5px;
}

</style>
