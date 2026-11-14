<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uiqcvh7cq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:audition-check" /></template>
<style>
.uiqcvh7cq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 2.5zA3.5 3.5 0 0 1 15 6v4a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 8 10V6a3.5 3.5 0 0 1 3.5-3.5m-6.5 8q0 .16.008.319t.023.318q.016.159.039.317q.024.158.055.314q.031.157.07.311q.039.155.085.308t.1.303t.115.297t.129.292t.144.285q.075.141.157.278t.17.269q.089.133.184.261t.196.252q.102.123.209.241t.22.231t.231.22t.241.209t.252.196t.261.184q.132.088.269.17t.278.157q.141.076.285.144t.292.129t.297.115t.303.1t.308.085t.311.07t.314.055t.317.039t.318.023t.319.008q.306 0 .611-.029m3.649-1.562q.263-.228.5-.483t.446-.533q.208-.279.386-.579q.177-.299.322-.616q.144-.317.254-.647t.184-.67t.111-.687T18 10.5M11.5 17v4.5m-3.5 0h6.3m.45-3.5l2 2L21 15.75");
}

</style>
