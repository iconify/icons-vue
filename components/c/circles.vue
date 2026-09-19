<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y44di6smb"/><circle class="hjrref-js"/><circle class="jmmb2pbah"/><circle class="akq9rggwp"/><circle class="mk0jb2bxt"/><circle class="g60n16bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:circles" /></template>
<style>
.akq9rggwp {
  cx: 35.303px;
  cy: 31.345px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g60n16bal {
  cx: 12.697px;
  cy: 24px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hjrref-js {
  cx: 21.331px;
  cy: 12.115px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jmmb2pbah {
  cx: 35.303px;
  cy: 16.655px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mk0jb2bxt {
  cx: 21.331px;
  cy: 35.885px;
  r: 8.613px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y44di6smb {
  cx: 25.193px;
  cy: 24px;
  r: 10.574px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
