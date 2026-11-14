<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hzo6bpqwr"/><path class="s6gxuacxc"/><path class="djr1nzvta"/><path class="wq-adheal"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:database-audit" /></template>
<style>
.djr1nzvta {
  d: path("M3.5 10.5a6 2.5 0 0 0 12 0M13 18q4.5-5 9 0q-4.5 5-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hzo6bpqwr {
  d: path("M3.5 5a6 2.5 0 1 0 12 0a6 2.5 0 1 0-12 0");
}

.s6gxuacxc {
  d: path("M3.5 5v11q0 .061.007.123q.007.061.022.122t.036.122t.05.121t.065.119t.078.119q.043.058.093.116q.049.058.106.115q.056.056.119.112q.063.055.132.109q.07.055.146.107q.075.053.157.104t.17.1q.087.05.181.097q.093.047.192.093q.099.045.203.089q.105.043.214.084t.223.081q.113.038.232.075q.118.037.241.071q.122.034.248.065q.127.032.257.061t.263.055t.269.05t.275.044q.138.021.279.038q.141.018.284.033t.287.027t.291.021q.145.009.292.015q.146.006.294.009q.147.003.294.003q.354 0 .706-.017m5.294-5.487V5");
}

.wq-adheal {
  d: path("M15.75 18a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
