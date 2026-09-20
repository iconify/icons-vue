<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq5t_dvtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compass-calibration-rounded" /></template>
<style>
.hq5t_dvtv {
  fill: currentColor;
  d: path("M9.165 19.22Q8 18.056 8 16.385t1.165-2.836T12 12.385t2.836 1.164T16 16.384q0 1.672-1.164 2.836Q13.67 20.385 12 20.385T9.165 19.22m.513-9.255q-1.122.348-2.074 1.046q-.242.18-.543.155t-.519-.243l-2.42-2.46q-.262-.261-.233-.624q.028-.364.32-.581q1.72-1.266 3.692-1.954Q9.873 4.615 12 4.615t4.099.689t3.692 1.954q.292.217.32.58q.03.364-.232.625l-2.421 2.46q-.217.218-.518.243t-.544-.155q-.952-.697-2.074-1.046T12 9.615t-2.322.35");
}

</style>
