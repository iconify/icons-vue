<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yzuwpfz6r"/><path class="tdi7bq-eq"/><path class="zbxt1mbvp"/><path class="fc-vc8hfa"/><circle class="z6jh3ibil"/><circle class="azotuxcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:busyboxinstaller" /></template>
<style>
.azotuxcjb {
  cx: 29.075px;
  cy: 11.178px;
  r: 0.75px;
  fill: currentColor;
}

.fc-vc8hfa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.315 15.72a10.685 10.685 0 1 1 21.37 0Zm4.274-8.549L15.452 4.5m14.959 2.671L32.548 4.5M22.397 32.815v3.206h3.206v-3.206Z");
}

.tdi7bq-eq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.041 24.801V43.5H38.96V24.801Z");
}

.yzuwpfz6r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.778 29.884l.755.756l-.755 1.511l.496 1.198l1.603.535v1.068l-1.603.534l-.496 1.198l.755 1.511l-.755.756l-1.511-.756l-1.199.497l-.534 1.602h-1.068l-.534-1.602l-1.199-.497l-1.51.756l-.756-.756l.755-1.51l-.496-1.199l-1.603-.534v-1.068l1.603-.535l.496-1.198l-.755-1.511l.755-.755l1.511.755l1.198-.496l.535-1.603h1.068l.535 1.603l1.198.496Z");
}

.z6jh3ibil {
  cx: 18.925px;
  cy: 11.178px;
  r: 0.75px;
  fill: currentColor;
}

.zbxt1mbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.041 24.801H7.438V18.39h33.124v6.411h-1.603M7.438 18.39l4.274-4.274h1.603m21.37 0h1.603l4.274 4.274");
}

</style>
