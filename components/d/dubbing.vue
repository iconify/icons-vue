<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6f9vx8tv"/><path class="g5p8j2b_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dubbing" /></template>
<style>
.g5p8j2b_s {
  d: path("M3 8.5q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284q.043.141.093.279q.049.139.106.275t.119.269t.132.263t.146.257t.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192t.232.181t.241.17t.248.157q.127.076.257.146t.263.132t.269.119t.275.106q.138.05.279.093t.284.078t.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.678 0 1.339-.151q.661-.152 1.271-.446m2.62-2.462q.378-.673.574-1.421Q15 9.273 15 8.5m-6 6v7m-3 0h5.4m4.35-7.5h4.5A1.75 1.75 0 0 1 22 15.75v4.5A1.75 1.75 0 0 1 20.25 22h-4.5A1.75 1.75 0 0 1 14 20.25v-4.5A1.75 1.75 0 0 1 15.75 14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6f9vx8tv {
  d: path("M9 2.5za3 3 0 0 1 3 3V9a3 3 0 0 1-3 3a3 3 0 0 1-3-3V5.5a3 3 0 0 1 3-3");
}

</style>
