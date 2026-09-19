<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yd8lnsw1c"/><circle class="t3dhkeb-h"/><path class="whvnjucde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lea-bos-mobil" /></template>
<style>
.t3dhkeb-h {
  cx: 36.221px;
  cy: 36.647px;
  r: 0.75px;
  fill: currentColor;
}

.whvnjucde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.384 13.986s-.83-.803-2.163-.803s-2.163.803-2.163.803m6.05-1.856s-1.465-1.527-3.875-1.527s-3.875 1.528-3.875 1.528");
}

.yd8lnsw1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 16.182v20.465h10.232m3.978-10.233h6.671m3.561 10.233H19.21V16.182h10.232m0 20.465l6.779-20.465L43 36.647");
}

</style>
