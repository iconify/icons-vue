<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="evc1vdotr"/><path class="lhwmaoh8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-phone-clone" /></template>
<style>
.evc1vdotr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.77 4.5a2.504 2.504 0 0 0-2.51 2.509v24.466a2.503 2.503 0 0 0 2.509 2.508H20.59v7.008a2.503 2.503 0 0 0 2.509 2.509h15.132a2.504 2.504 0 0 0 2.509-2.509V16.525a2.503 2.503 0 0 0-2.51-2.508H27.416V7.009a2.504 2.504 0 0 0-2.51-2.509Z");
}

.lhwmaoh8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.589 33.983l-.001-17.458a2.503 2.503 0 0 1 2.509-2.509h4.317M25.28 38.888l10.183-.054M13.232 12.231l17.113 19.246m.533-5.971l-.533 5.971m-5.704.586l5.704-.586");
}

</style>
