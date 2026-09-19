<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="opurzibrl"/><path class="trf1ki9md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:freeagent" /></template>
<style>
.opurzibrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.296 31.453H24.567m-9.341 10.949L28.479 9.475L41.731 42.5");
}

.trf1ki9md {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.479 9.475c1.422-3.535 3.878-5.178 8.333-2.98M6.269 7.697c4.602 3.052 9.35.645 14.1.645c5.158 0 4.308 7.093 3.839 11.783c-1.524-2.902-3.517-3.752-5.305-3.4c-1.789.352-5.6 1.524-7.153.205s-4.778-5.104-5.48-9.233Z");
}

</style>
