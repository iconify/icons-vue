<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="qcjjjgwrj"/><path class="wl71-_2jx"/></g><g class="to-5kdesz"><path class="wfpy3gbmy"/><path class="lw4f_pt4y"/><path class="is-ytvijl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-kash-9" /></template>
<style>
.is-ytvijl {
  d: path("M39.9 16.105a3.985 3.985 0 1 0 0-7.97c-.086 0-.167.02-.253.025c-.653-2.124-2.608-3.677-4.946-3.677S30.41 6.036 29.755 8.16c-.085-.005-.166-.025-.252-.025a3.985 3.985 0 1 0 0 7.97z");
}

.lw4f_pt4y {
  stroke-linecap: round;
  d: path("M39.9 16.105v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953m-12.96-3l.015 6");
}

.qcjjjgwrj {
  cx: 23.349px;
  cy: 29.659px;
  r: 3.733px;
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.wfpy3gbmy {
  stroke-linecap: round;
  d: path("M39.9 19.661h-33m33-3.556v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953");
}

.wl71-_2jx {
  d: path("M20.03 35.743c.554.83 1.522 1.382 3.043 1.382h.276a3.72 3.72 0 0 0 3.733-3.733v-3.733");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
