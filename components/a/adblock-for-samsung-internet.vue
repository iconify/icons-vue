<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uc3gb2bpf"/><path class="v6hgdmb8e"/><path class="shw_p8bsy"/><path class="ctnnjtb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adblock-for-samsung-internet" /></template>
<style>
.ctnnjtb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.663 5.5H16.337L5.5 16.337v15.326L16.337 42.5h15.326L42.5 31.663V16.337z");
}

.shw_p8bsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.549 14.044c0-1.981 3.214-2.239 3.214.024v11.637l1.62-3.387a2.44 2.44 0 0 1 2.154-1.5l1.693.048c.073.003.106.273.025.509l-4.017 11.589a6.14 6.14 0 0 1-3.58 3.725a8.09 8.09 0 0 1-7.235-.024c-2.67-1.434-3.524-3.945-3.725-6.363l.024-13.065a1.498 1.498 0 0 1 2.983-.236");
}

.uc3gb2bpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.57 22.609l-.025-10.355c-.216-2.488-3.208-2.265-3.315 0l-.097 10.282");
}

.v6hgdmb8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.219 13.49c.061-1.89-3.384-2.132-3.449.36c0 0-.193 9.122-.072 9.098");
}

</style>
