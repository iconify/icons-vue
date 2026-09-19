<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="huq2su-yu"/><circle class="gmxt364bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:curiositystream" /></template>
<style>
.gmxt364bx {
  cx: 24px;
  cy: 40.23px;
  r: 3.34px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.huq2su-yu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.8 4.58v16a9.2 9.2 0 0 0 18.4 0v-16M24 33.86v-4.09");
}

</style>
