<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2e8aqbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-fill" /></template>
<style>
.d2e8aqbdi {
  fill: currentColor;
  d: path("M3.004 5.331q.052-.03.106-.056l.004-.002l8-3.951a2 2 0 0 1 .872-.207h.028c.303.003.6.073.872.207l4.055 2.003l.002.001l3.603 1.779l.002.001l.338.167A2 2 0 0 1 22 7.066V12a1 1 0 0 1-2 0V8.054l-5.742 2.835ZM12 12.004l1 .494V21a1.62 1.62 0 0 1-2.337 1.455l-7.549-3.728A2 2 0 0 1 2 16.934V7.066ZM21 17a1 1 0 0 1 0 2h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L17.414 17Z");
}

</style>
