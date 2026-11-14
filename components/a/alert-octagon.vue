<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twzu7fqmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alert-octagon" /></template>
<style>
.twzu7fqmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 3.761L20.239 7.5a2.63 2.63 0 0 1 .769 1.856v5.288a2.63 2.63 0 0 1-.769 1.856L16.5 20.239a2.63 2.63 0 0 1-1.856.769H9.356a2.63 2.63 0 0 1-1.856-.769L3.761 16.5a2.63 2.63 0 0 1-.769-1.856V9.356A2.63 2.63 0 0 1 3.761 7.5L7.5 3.761a2.63 2.63 0 0 1 1.856-.769h5.288a2.63 2.63 0 0 1 1.856.769M12 7v6m0 3.5h.01");
}

</style>
