<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="alo1cc6hb"/><circle class="i4evxpt9q"/><path class="p2c3-xbff"/><path class="u61fwzqpr"/><path class="hqahhmb2x"/><path class="x8prbsb-e"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:itsme" /></template>
<style>
.alo1cc6hb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.317 31.756a3.611 3.611 0 0 1 7.222 0v5.778m-7.223-9.389v9.389m7.223-5.778a3.611 3.611 0 0 1 7.222 0v5.778m8.985-1.806a3.5 3.5 0 0 1-3.07 1.805a3.62 3.62 0 0 1-3.611-3.61v-2.348a3.611 3.611 0 0 1 7.222 0v1.264h-7.222");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hqahhmb2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.141 13.756h2.65");
}

.i4evxpt9q {
  cx: 12.405px;
  cy: 11.697px;
  r: 0.75px;
  fill: currentColor;
}

.p2c3-xbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.69 23.238a4.57 4.57 0 0 0 3.095.774h.775a2.516 2.516 0 0 0 0-5.031h-1.742a2.516 2.516 0 0 1 0-5.031h.774c1.742 0 2.516.193 3.096.774");
}

.u61fwzqpr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 8.148;
  d: path("M12.4 22.077a1.827 1.827 0 0 0 1.934 1.935a3.6 3.6 0 0 0 2.613-.774m.194-12.772v11.61a1.827 1.827 0 0 0 1.935 1.936a3.6 3.6 0 0 0 2.613-.774");
}

.x8prbsb-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 8.148;
  d: path("m12.4 22.077l.006-8.32");
}

</style>
