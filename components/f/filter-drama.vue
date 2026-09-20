<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4lhn__uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-drama" /></template>
<style>
.q4lhn__uo {
  fill: currentColor;
  d: path("M6.5 19q-1.877 0-3.189-1.311T2 14.5q0-1.748 1.251-3.009t3.018-1.26q1.748 0 3.009 1.26t1.26 3.009h1q0-2.19-1.417-3.659t-3.679-1.61q.431-1.908 2-3.07T12 5q2.508 0 4.254 1.746T18 11v1h.616q1.401 0 2.393 1.035T22 15.5q0 1.452-1.024 2.476T18.5 19z");
}

</style>
