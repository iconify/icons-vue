<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h6xgfc01c"/><path class="qfdi99wyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:episteme" /></template>
<style>
.h6xgfc01c {
  cx: 33.689px;
  cy: 33.395px;
  r: 8.811px;
  fill: none;
  stroke: currentColor;
}

.qfdi99wyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.235 21.493V9.318a3.524 3.524 0 0 0-3.524-3.524h-9.196m0 34.378H9.48a3.524 3.524 0 0 1-3.524-3.465L5.5 9.377a3.524 3.524 0 0 1 3.524-3.583h4.577m0 0v15.7l4.348-2.673l4.566 2.672V5.794m-8.914 0h8.914m8.71 23.377l7.104 4.47l-7.105 4.01z");
}

</style>
