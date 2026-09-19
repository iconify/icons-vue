<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yn8vx4bpy"/><path class="n4vmzxbyg"/></g><g class="to-5kdesz"><path class="wfpy3gbmy"/><path class="lw4f_pt4y"/><path class="is-ytvijl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-kash-31" /></template>
<style>
.is-ytvijl {
  d: path("M39.9 16.105a3.985 3.985 0 1 0 0-7.97c-.086 0-.167.02-.253.025c-.653-2.124-2.608-3.677-4.946-3.677S30.41 6.036 29.755 8.16c-.085-.005-.166-.025-.252-.025a3.985 3.985 0 1 0 0 7.97z");
}

.lw4f_pt4y {
  stroke-linecap: round;
  d: path("M39.9 16.105v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953m-12.96-3l.015 6");
}

.n4vmzxbyg {
  d: path("M15.514 26.97c.775-.646 1.61-.94 3.486-.936l.435.003a2.8 2.8 0 0 1 2.8 2.799h0a2.8 2.8 0 0 1-2.8 2.8m-2.152-.001h2.152m6.949-4.15l2.8-1.54m0 0v11.199");
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

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yn8vx4bpy {
  d: path("M15.516 36.29c.773.647 1.608.944 3.482.944h.437a2.8 2.8 0 0 0 2.8-2.8h0a2.8 2.8 0 0 0-2.8-2.799");
}

</style>
