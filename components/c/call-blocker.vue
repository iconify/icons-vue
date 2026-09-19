<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kscezrbmj"/><circle class="cpk0fnbgt"/><path class="fst9hrb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:call-blocker" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fst9hrb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.799 39.201L39.201 8.799");
}

.kscezrbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.468 16.547a16.3 16.3 0 0 1-.597-2.969c-.106-1.002-.981-1.748-1.99-1.748h-4.678c-1.203 0-2.13 1.039-2.024 2.237c1.067 12.072 10.683 21.688 22.755 22.754c1.198.106 2.237-.817 2.237-2.02v-4.17c0-1.523-.746-2.395-1.749-2.501a16.3 16.3 0 0 1-2.968-.597a3.32 3.32 0 0 0-3.298.842l-2.002 2.002a21.17 21.17 0 0 1-8.53-8.53l2.001-2.002a3.32 3.32 0 0 0 .843-3.298");
}

</style>
