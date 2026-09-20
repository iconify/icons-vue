<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="grcmjq4yh"/><path class="mz9fpkbij"/><path class="umi34zz3g"/><path class="xew4tlsta"/><circle class="ityysac-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-forms" /></template>
<style>
.grcmjq4yh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 6.993h12.657a6.086 6.086 0 0 1 0 12.171H23.758a6.086 6.086 0 0 1 0-12.171m-.001 24.343h12.657a6.086 6.086 0 0 1 0 12.171H23.758a6.086 6.086 0 0 1 0-12.171");
}

.ityysac-j {
  cx: 11.585px;
  cy: 13.079px;
  r: 2.921px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mz9fpkbij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.586 31.336za6.086 6.086 0 0 1 0 12.171a6.086 6.086 0 0 1 0-12.171m0-12.171za6.086 6.086 0 0 1 0 12.171a6.086 6.086 0 0 1 0-12.171");
}

.umi34zz3g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 19.165h12.657a6.086 6.086 0 0 1 0 12.171H23.758a6.086 6.086 0 0 1 0-12.171m-.001-12.172h12.657a6.086 6.086 0 0 1 0 12.171H23.758a6.086 6.086 0 0 1 0-12.171");
}

.xew4tlsta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.586 6.993za6.086 6.086 0 0 1 0 12.171a6.086 6.086 0 0 1 0-12.171m12.171 6.086h12.657");
}

</style>
