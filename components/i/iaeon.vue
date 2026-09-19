<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qrt7lrytu"/><path class="w5alf5bfz"/><path class="pbvy5obhw"/><path class="rqv9rfbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iaeon" /></template>
<style>
.pbvy5obhw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.924 17.639l.46 1.258a17.5 27.5 0 0 0-.46-1.258m1.908 6.834l.514 3.88a17.5 27.5 0 0 0-.514-3.88");
}

.qrt7lrytu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.489 16.075C25.894 16.518 13 18.812 13 21.5s12.894 4.982 30.489 5.425l.01 8.06c-21.538 0-39-4.918-39-10.985s17.462-10.985 39-10.985z");
}

.rqv9rfbdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.712 14.922a38 24 0 0 1-15.98 6.406");
}

.w5alf5bfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.577 30.703a37 6 0 0 1 21.58-4.22");
}

</style>
