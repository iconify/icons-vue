<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i7m_kac6x"/><path class="zyszz753t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-construction-sign" /></template>
<style>
.i7m_kac6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.66 28.43v-4.186m2.756 9.581v4.293c0 .443-.36.803-.803.803H9.46a.803.803 0 0 1-.802-.803v-4.004m2.758-9.871v4.187M8.66 18.881v-3.895m2.757 0v3.833m25.18 9.988v-4.565m2.757 9.874v4.003c0 .444-.36.803-.803.803h-1.153a.803.803 0 0 1-.802-.803v-4.003m2.758-9.873v3.937m-2.757-9.437v-3.885m2.758 0v3.822M5.5 18.94h37v5.02h-37z");
}

.zyszz753t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 28.807h37v5.02h-37zm1.508-16.699a3.03 3.03 0 0 0 6.06.002v-.002a3.03 3.03 0 0 0-6.06 0m27.938 0a3.03 3.03 0 1 0 6.06 0a3.03 3.03 0 0 0-6.06 0");
}

</style>
