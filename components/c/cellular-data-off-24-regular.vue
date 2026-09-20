<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n515h9a7m"/><path class="ouqaubhqk"/><path class="vejycwbem"/><path class="z0xq73bum"/><path class="t2ddm0b-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-off-24-regular" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n515h9a7m {
  d: path("M3.28 2.22a.75.75 0 1 0-1.06 1.06L11 12.06v7.19l.007.102a.75.75 0 0 0 1.493-.102v-5.69l2.5 2.5v3.19l.007.102a.75.75 0 0 0 1.493-.102v-1.69l4.22 4.22a.75.75 0 0 0 1.06-1.06L3.28 2.22z");
  fill: currentColor;
}

.ouqaubhqk {
  d: path("M19 15.818l1.5 1.5V5.742l-.008-.101A.75.75 0 0 0 19 5.757v10.061z");
  fill: currentColor;
}

.t2ddm0b-b {
  d: path("M7.75 14a.75.75 0 0 1 .743.648l.007.102v4.499a.75.75 0 0 1-1.493.102L7 19.248V14.75a.75.75 0 0 1 .75-.75z");
  fill: currentColor;
}

.vejycwbem {
  d: path("M15 11.818l1.5 1.5V8.75l-.007-.102A.75.75 0 0 0 15 8.75v3.068z");
  fill: currentColor;
}

.z0xq73bum {
  d: path("M3.75 17a.75.75 0 0 1 .743.648l.007.102v1.5a.75.75 0 0 1-1.493.102L3 19.25v-1.5a.75.75 0 0 1 .75-.75z");
  fill: currentColor;
}

</style>
