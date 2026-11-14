<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tewa8g8ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cold-plunge-tub" /></template>
<style>
.tewa8g8ji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5V12q0 .147.007.294q.007.148.022.294q.014.147.036.292q.022.146.05.291q.029.144.065.287t.078.284q.043.141.093.279q.049.139.106.275t.119.269t.132.263t.146.257t.157.248q.082.123.17.241q.087.119.181.232q.093.114.192.223t.203.214q.105.104.214.203t.223.192q.113.094.232.181q.118.088.241.17q.122.082.248.157q.127.076.257.146t.263.132t.269.119t.275.106q.138.05.279.093t.284.078q.143.036.287.065q.145.028.291.05q.145.022.292.036q.146.015.294.022Q8.853 18 9 18h3.016m8.94-5.275Q21 12.364 21 12V7.5m-18 0q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0m-2.5 8v6M15.75 17l5.5 3m-5.5 0l5.5-3");
}

</style>
