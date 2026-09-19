<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><g class="n1mjunbsu"><circle class="ead9wrb6u"/><circle class="kt-s460-u"/><circle class="g8uvvacuj"/><circle class="prj032h0j"/><circle class="xdk2pf6ta"/><circle class="edl-4f0by"/><path class="xtxx_mrjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:baggage-claim" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.ead9wrb6u {
  cx: 14.5px;
  cy: 48px;
  r: 2px;
}

.edl-4f0by {
  cx: 49.5px;
  cy: 48px;
  r: 2px;
}

.g8uvvacuj {
  cx: 28.5px;
  cy: 48px;
  r: 2px;
}

.kt-s460-u {
  cx: 21.5px;
  cy: 48px;
  r: 2px;
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.prj032h0j {
  cx: 35.5px;
  cy: 48px;
  r: 2px;
}

.xdk2pf6ta {
  cx: 42.5px;
  cy: 48px;
  r: 2px;
}

.xtxx_mrjw {
  d: path("M41 19h-2v-3.9c0-.6-.4-1-1-1H26c-.6 0-1 .5-1 1V19h-2v-3.9c0-1.7 1.3-3.1 3-3.1h12c1.7 0 3 1.4 3 3.1zm9 0h-3.5v24H50c1.1 0 2-.9 2-2V21c0-1.1-.9-2-2-2m-30.5 0h25v24h-25zm-2 0H14c-1.1 0-2 .9-2 2v20c0 1.1.9 2 2 2h3.5z");
}

</style>
