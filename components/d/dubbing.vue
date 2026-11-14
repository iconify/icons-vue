<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i_0db1b8e"/><path class="g_cqt7buv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dubbing" /></template>
<style>
.g_cqt7buv {
  d: path("M3 8.5q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284q.043.141.093.279q.049.139.106.275t.119.269t.132.263t.146.257t.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192t.232.181t.241.17t.248.157q.127.076.257.146t.263.132t.269.119t.275.106q.138.05.279.093t.284.078t.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022q.147.007.294.007q.572 0 1.134-.108t1.093-.321m3.151-2.911q.307-.62.464-1.294T15 8.5m-6 6v7m-3 0h5.2M14 14h8v8h-8Z");
}

.i_0db1b8e {
  d: path("M11.236 11.972Q11.12 12 11 12H7q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151t-.093-.173t-.057-.188T6 11V3.5q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T7 2.5h4q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188T12 3.5V11q0 .097-.018.191");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
