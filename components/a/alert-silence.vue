<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdbbmzoxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alert-silence" /></template>
<style>
.hdbbmzoxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.59 17.5H4.5L6 16v-5.5q0-.283.027-.564m3.11-4.709q.659-.358 1.386-.542T12 4.5q.147 0 .294.007q.148.007.294.022q.147.014.292.036q.146.022.291.05q.144.029.287.065t.284.078t.279.093q.139.049.275.106t.269.119t.263.132t.257.146q.126.075.248.157q.123.082.241.17q.119.087.232.181q.114.093.223.192t.214.203q.104.105.203.214t.192.223q.094.113.181.232q.088.118.17.241q.082.122.157.248q.076.127.146.257t.132.263t.119.269t.106.275q.05.138.093.279t.078.284q.036.143.065.287q.028.145.05.291q.022.145.036.292q.015.146.022.294q.007.147.007.294v3.531M12 2.5v2m-2 16h4M3.5 3.5l17 17");
}

</style>
