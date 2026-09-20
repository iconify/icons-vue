<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><g transform="translate(3 3)"><path clip-rule="evenodd" class="i8n8cc_hw"/><circle class="odkqjcchh"/><circle class="uq5fhnb9e"/><circle class="cxfni2ljt"/></g><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:calendar-circle" /></template>
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

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
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

</style>
