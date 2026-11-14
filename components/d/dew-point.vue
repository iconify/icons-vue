<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lre11rbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dew-point" /></template>
<style>
.lre11rbmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.448 11.67C14.879 7.215 10.5 2.5 10.5 2.5S4 9.5 4 14.5q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297q.061.148.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209q.124.101.252.196t.261.184q.132.088.269.17t.278.157t.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055q.158.023.317.039q.159.015.318.023T10.5 21q.643 0 1.274-.126t1.225-.374m3.751-2.75V15.5a1.25 1.25 0 0 1 2.5 0v2.25a2.25 2.25 0 1 1-2.5 0Z");
}

</style>
