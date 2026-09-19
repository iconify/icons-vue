<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qq4c_blss"/><path class="betgmc3ck"/><path class="o9gv__bkg"/><path class="nt8avg55p"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anikku" /></template>
<style>
.betgmc3ck {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.844 32.984c1.002 2.571 2.739 3.673 2.739 3.673c2.204-6.278-.301-22.008-.301-22.008M12.729 27.707c1.436-3.173 4.67-5.85 4.67-5.85m-2.833-7.609c1.803 1.103 2.37 2.271 2.37 2.271");
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

.nt8avg55p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.816 11.343c1.503 1.737.056 6.758.257 9.764c-2.586-2.901-3.588-5.4-3.588-5.4l2.907-.323");
}

.o9gv__bkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.924 13.914c3.273 1.403 4.328 2.532-4.248 3.587");
}

.qq4c_blss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.564 22.63c5.844-1.502 17.666-2.437 21.707-.867c-.768 1.202-3.072 1.736-3.072 1.736");
}

</style>
