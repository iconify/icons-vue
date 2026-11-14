<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1fz8fyof"/><path class="rthvkibkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hydrafacial" /></template>
<style>
.k1fz8fyof {
  d: path("M17.439 14.39q.061-.443.061-.89c0-4-6.5-11-6.5-11s-6.5 7-6.5 11q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297q.061.148.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209q.124.101.252.196t.261.184q.132.088.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023T11 20q.455 0 .905-.063q.451-.064.888-.189q.437-.126.852-.311q.416-.185.801-.426");
}

.rthvkibkl {
  d: path("M8 13.5a3 3 0 0 0 3 3m7-1.5q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
