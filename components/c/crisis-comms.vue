<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fp89_vbiz"/><path class="ioogjqbsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crisis-comms" /></template>
<style>
.fp89_vbiz {
  d: path("M11 2.5zA3.5 3.5 0 0 1 14.5 6v4a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 7.5 10V6A3.5 3.5 0 0 1 11 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ioogjqbsv {
  d: path("M4.5 10.5q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055t.317.039t.318.023T11 17q.569 0 1.129-.099q.56-.098 1.094-.293t1.027-.479t.928-.65m2.14-3.45q.182-.754.182-1.529M11 17v4m-3.5 0h7m3.5-6.25v3.5M18 21h.01");
}

</style>
