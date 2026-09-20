<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="i8n8cc_hw"/><circle class="odkqjcchh"/><circle class="uq5fhnb9e"/><circle class="cxfni2ljt"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:calendar-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.cxfni2ljt {
  cx: 14.5px;
  cy: 4.5px;
  r: 1.5px;
}

.i8n8cc_hw {
  fill-rule: evenodd;
  d: path("M3 4h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1m1 4v8h12V8z");
}

.odkqjcchh {
  cx: 6.5px;
  cy: 10.5px;
  r: 1.5px;
}

.uq5fhnb9e {
  cx: 5.5px;
  cy: 4.5px;
  r: 1.5px;
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
