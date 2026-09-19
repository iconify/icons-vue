<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iqnfx6b2c"/><circle class="o6019qbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hermine-thw" /></template>
<style>
.iqnfx6b2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.526 40.662l.623 4.838h3.677l.644-4.838l3.719-.995l2.958 3.878l3.184-1.837l-1.86-4.512l2.723-2.721l4.501 1.879l1.838-3.184l-3.868-2.977l.997-3.716l4.838-.626v-3.675l-4.838-.646l-.993-3.717l3.876-2.96l-1.837-3.184l-4.512 1.86l-2.721-2.72l1.879-4.502l-3.184-1.84l-2.977 3.868l-3.716-.997L25.85 2.5h-3.675l-.646 4.838l-3.717.995l-2.96-3.878l-3.184 1.837l1.86 4.512l-2.72 2.722l-4.502-1.878l-1.84 3.182l3.868 2.977l-.997 3.719l-4.838.623v3.677l4.838.644l.995 3.717l-3.878 2.96l1.837 3.184l4.512-1.86l2.722 2.723l-1.878 4.501l3.184 1.838l2.977-3.868z");
}

.o6019qbhq {
  cx: 24.003px;
  cy: 24.001px;
  r: 14.183px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
