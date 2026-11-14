<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgkeuwbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-trip-buoy" /></template>
<style>
.tgkeuwbbj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V19M6 9.5h7M3.5 13q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284q.043.141.093.279q.049.139.106.275t.119.269t.132.263t.146.257q.075.126.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192q.113.094.232.181q.118.088.241.17q.122.082.248.157q.127.076.257.146t.263.132t.269.119t.275.106q.138.05.279.093t.284.078q.143.036.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.526 0 1.044-.092q.518-.091 1.012-.271t.949-.444t.858-.602m1.892-2.894q.245-.831.245-1.697m.5 6a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75-2.75v-2.5");
}

</style>
