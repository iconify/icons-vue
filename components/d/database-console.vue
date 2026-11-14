<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5oqpsb0x"/><path class="zoevy3b8j"/><path class="dz-lb4bwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-console" /></template>
<style>
.dz-lb4bwx {
  d: path("M3.5 10.75q0 .061.007.123q.007.061.022.122t.036.122t.05.121t.065.119t.078.119q.043.058.093.116q.049.058.106.115q.056.056.119.112q.063.055.132.109q.07.055.146.107q.075.053.157.104t.17.1q.087.05.181.097q.093.047.192.093q.099.045.203.089q.105.043.214.084t.223.081q.113.038.232.075q.118.037.241.071q.122.034.248.065q.127.032.257.061t.263.055t.269.05q.136.023.275.044q.138.021.279.038q.141.018.284.033t.287.027t.291.021q.145.009.292.015q.146.006.294.009q.147.003.294.003q1.347 0 2.565-.24m2.73-1.084q.347-.272.526-.57t.179-.606M14 15l3.25 2.75L14 20.5m5 0h3");
}

.i5oqpsb0x {
  d: path("M3.5 5a6 2.5 0 1 0 12 0a6 2.5 0 1 0-12 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zoevy3b8j {
  d: path("M3.5 5v11.5q0 .061.007.123q.007.061.022.122t.036.122t.05.121t.065.119t.078.119q.043.058.093.116q.049.058.106.115q.056.056.119.112q.063.055.132.109q.07.055.146.107q.075.053.157.104t.17.1q.087.05.181.097q.093.047.192.093q.099.045.203.089q.105.043.214.084t.223.081q.113.038.232.075q.118.037.241.071q.122.034.248.065q.127.032.257.061t.263.055t.269.05t.275.044q.138.021.279.038q.141.018.284.033t.287.027t.291.021q.145.009.292.015q.146.006.294.009q.147.003.294.003q1.115 0 2.156-.167m3.844-6.237V5");
}

</style>
