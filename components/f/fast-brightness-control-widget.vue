<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="lck00867x"/><path class="hu3xlobnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fast-brightness-control-widget" /></template>
<style>
.hu3xlobnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.082 36.095l.086 6.136l-5.634-2.433l-2.27 5.702l-4.274-4.404l-4.278 4.398l-2.265-5.704l-5.635 2.427l.092-6.136l-6.136.087L8.2 30.533l-5.7-2.268l4.403-4.275l-4.397-4.278l5.704-2.263l-2.427-5.637l6.137.093l-.087-6.136l5.633 2.433l2.27-5.702l4.274 4.403l4.278-4.399l2.265 5.704l5.635-2.425l-.091 6.134l6.135-.085l-2.433 5.635l5.701 2.268l-4.403 4.275l4.398 4.278l-5.703 2.263l2.427 5.636ZM6.903 23.99l34.193.019");
}

.lck00867x {
  cx: 24.008px;
  cy: 23.971px;
  r: 11.516px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
