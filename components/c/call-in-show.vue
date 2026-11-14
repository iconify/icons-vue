<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qzeft46xx"/><path class="n63hwfbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:call-in-show" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n63hwfbyj {
  d: path("M3 9.5q0 .16.008.319t.023.318t.039.317t.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285t.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115q.15.054.303.1t.308.085t.311.07t.314.055t.317.039t.318.023T9.5 16q.569 0 1.129-.099q.56-.098 1.094-.293t1.027-.479t.928-.65m.767-.76q.373-.438.664-.935q.291-.496.49-1.036t.3-1.106T16 9.5M9.5 16v5.5m-3 0h6M16 16h2l1 2.25l-1.25 1c.5 1 1 1.5 2 2l1-1.25l1.25.75V22h-1c-2.75 0-5-2.25-5-5Z");
}

.qzeft46xx {
  d: path("M9.5 2.5zA3.5 3.5 0 0 1 13 6v3.5A3.5 3.5 0 0 1 9.5 13A3.5 3.5 0 0 1 6 9.5V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
