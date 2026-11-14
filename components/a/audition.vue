<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lu09fy6wb"/><path class="anq_9ccfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audition" /></template>
<style>
.anq_9ccfb {
  d: path("M3.5 10q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284q.043.141.093.279q.049.139.106.275t.119.269t.132.263t.146.257q.075.126.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192t.232.181t.241.17t.248.157q.127.076.257.146t.263.132t.269.119t.275.106q.138.05.279.093t.284.078t.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.242 0 .484-.02m4.274-2.325q.3-.39.532-.824t.391-.901q.158-.466.239-.952T15.5 10m-6 6v4.5m-3 0h6m5.25-6.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.lu09fy6wb {
  d: path("M7.5 2.5h4A1.5 1.5 0 0 1 13 4v7.5a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 6 11.5V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
