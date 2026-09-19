<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wvn5qobiy"/><path class="fvczepy0a"/><path class="oi5qdnbpn"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bang-and-olufsen" /></template>
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

.fvczepy0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.854 26.813c4.904 0 7.93-3.316 7.93-7.407S17.758 12 12.854 12v23.95c4.127.379 6.075-1.486 6.075-4.569s-1.948-4.948-6.075-4.57m17.313-14.233a1.743 1.743 0 1 0-2.465 2.465l5.34 5.34");
}

.oi5qdnbpn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.041 16.673l-3.198 3.199a1.743 1.743 0 1 1-2.465-2.465l1.344-1.344");
}

.wvn5qobiy {
  cx: 28.884px;
  cy: 29.69px;
  r: 6.262px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
