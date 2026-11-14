<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5uajpb2b"/><path class="wpdovnb7z"/><path class="auen9ubww"/><path class="xc8sd__xl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-restore" /></template>
<style>
.auen9ubww {
  d: path("M3 10.5a6 2.5 0 0 0 12 0m-1.5 7a4 4 0 1 0 4-4");
}

.b5uajpb2b {
  d: path("M3 5a6 2.5 0 1 0 12 0A6 2.5 0 1 0 3 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wpdovnb7z {
  d: path("M3 5v11q0 .061.007.123q.007.061.022.122t.036.122t.05.121t.065.119t.078.119q.043.058.093.116q.049.058.106.115q.056.056.119.112q.063.055.132.109q.07.055.146.107q.075.053.157.104t.17.1q.087.05.181.097q.093.047.192.093q.099.045.203.089q.105.043.214.084t.223.081q.113.038.232.075q.118.037.241.071q.122.034.248.065q.127.032.257.061t.263.055t.269.05t.275.044q.138.021.279.038q.141.018.284.033t.287.027t.291.021q.145.009.292.015q.146.006.294.009q.147.003.294.003q.89 0 1.742-.108M15 15.096v-.4m0-2.4V5");
}

.xc8sd__xl {
  d: path("M19.25 11.75L17.5 13.5l1.75 1.75");
}

</style>
