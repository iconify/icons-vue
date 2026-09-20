<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s14em-yxa"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:c-and-a" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.s14em-yxa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.333 26.331H26.8c-.304 0-.685-.152-.837-.456l-2.131-2.893c-.304-.38-.761-.837-.761-1.522s.533-1.218 1.294-1.218c.685 0 1.218.533 1.218 1.218s-.533 1.294-1.599 1.522c-1.141.229-1.902.838-1.902 1.903c0 .837.532 1.446 1.598 1.446c1.37 0 2.207-1.37 3.425-2.968m9.557 3.292h-7.351m-1.838 5.514l5.513-16.337L38.5 32.169m-17.972-5.61za5.49 5.49 0 0 1-5.514 5.514c-3.063 0-5.514-2.451-5.514-5.31V21.25c0-3.063 2.45-5.513 5.514-5.31c3.063 0 5.31 2.451 5.31 5.31");
}

</style>
