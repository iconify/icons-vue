<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ie5lkwbxy"/><path class="gd55t1baa"/><path class="idvmkmbzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-formula-tin" /></template>
<style>
.gd55t1baa {
  d: path("M3 7v11.5q0 .055.007.11q.007.056.022.111t.036.109t.05.109t.065.108t.078.106q.043.053.093.105q.049.052.106.103t.119.101t.132.099q.07.048.146.096q.075.047.157.093t.17.09q.087.045.181.087q.093.043.192.084t.203.08q.105.039.214.076t.223.072t.232.068t.241.064l.248.059q.127.028.257.054t.263.05t.269.045t.275.039q.138.019.279.035t.284.03t.287.024t.291.019q.145.008.292.013q.146.006.294.008q.147.003.294.003q.792 0 1.557-.077t1.45-.226M15 14.728V7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.idvmkmbzo {
  d: path("M3 10a6 2.25 0 0 0 12 0m-1 7.5h6a3 3 0 0 1-6 0m6 0l1.75-4.5");
}

.ie5lkwbxy {
  d: path("M3 7a6 2.25 0 1 0 12 0A6 2.25 0 1 0 3 7");
}

</style>
