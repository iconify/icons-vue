<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="nhpf2fb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hp" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nhpf2fb4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.985 21.725c1.248-3.866 4.947-7 8.26-7c3.314 0 4.988 3.134 3.74 7l-3.73 11.55m6.26-7c-1.248 3.866.426 7 3.74 7s7.012-3.134 8.26-7l1.47-4.55c1.248-3.866-.427-7-3.74-7s-7.012 3.134-8.26 7m-19.73 11.55l9.652-29.89m12.338 11.34l-9.83 30.441");
}

</style>
