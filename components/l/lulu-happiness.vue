<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgnniiz6q"/><path class="hb9ijtpkd"/><path class="vyijydxqe"/><path class="xm9uzjeuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lulu-happiness" /></template>
<style>
.dgnniiz6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.663 24.317c-1.109.947-1.884 1.979-2.177 3.3");
}

.hb9ijtpkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.376 25.68c6.098 5.17 11.529 6.212 17.723 4.799c6.194-1.414 11.358-7.965 12.85-13.166");
}

.vyijydxqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.154 16.771c1.433.27 2.619.78 3.53 1.781m-18.842 2.385a1.758 1.758 0 0 1-3.417.826h0a1.76 1.76 0 0 1 1.295-2.121h0a1.76 1.76 0 0 1 2.122 1.295m6.705-1.621a1.758 1.758 0 1 1-2.122-1.296h0a1.76 1.76 0 0 1 2.122 1.296");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
