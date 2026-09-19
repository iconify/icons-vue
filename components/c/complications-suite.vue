<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wn9edfbhg"/><path class="lq2s-zbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:complications-suite" /></template>
<style>
.lq2s-zbim {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.432 12.453l-1.31-5.674A2.94 2.94 0 0 0 28.256 4.5h-8.513a2.94 2.94 0 0 0-2.865 2.279l-1.31 5.67m0 23.099l1.31 5.673a2.94 2.94 0 0 0 2.865 2.279h8.513a2.94 2.94 0 0 0 2.865-2.279l1.31-5.674M17.196 17.196h5.103v5.103h-5.103zm0 8.505h5.103v5.103h-5.103zm8.505 0h5.103v5.103h-5.103zm2.552-9.561l-3.609 3.608l3.609 3.608l3.609-3.608z");
}

.wn9edfbhg {
  cx: 24px;
  cy: 24px;
  r: 14.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
