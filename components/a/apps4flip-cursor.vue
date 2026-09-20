<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(24.867 17.402 25.965)" class="zkph9ns3b"/><path class="bvc9v94-b"/><rect transform="rotate(24.867 20.238 19.845)" class="z8cui692k"/><path class="pnzrn4bci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apps4flip-cursor" /></template>
<style>
.bvc9v94-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8.715 20.305l18.62 8.63");
}

.pnzrn4bci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.011 22.493l-.986 2.127m3.441-7.424l1.897-4.093m0 0l.3-.648a7.29 7.29 0 1 1 13.23 6.132l-2.625 5.663a3.833 3.833 0 0 0 6.956 3.224L42.5 24.72");
}

.z8cui692k {
  width: 3.804px;
  height: 5.838px;
  x: 18.337px;
  y: 16.926px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.902px;
  ry: 1.902px;
}

.zkph9ns3b {
  width: 20.522px;
  height: 28.351px;
  x: 7.141px;
  y: 11.789px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.261px;
  ry: 10.261px;
}

</style>
