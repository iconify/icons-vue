<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgv4xs74f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compass-calibration-outline-rounded" /></template>
<style>
.vgv4xs74f {
  fill: currentColor;
  d: path("M9.165 19.22Q8 18.056 8 16.385t1.165-2.836T12 12.385t2.836 1.164T16 16.384q0 1.672-1.164 2.836Q13.67 20.385 12 20.385T9.165 19.22m4.96-.71q.875-.876.875-2.126t-.875-2.125T12 13.385t-2.125.875T9 16.385t.875 2.125t2.125.875t2.125-.875M9.678 9.965q-1.122.35-2.074 1.047q-.236.18-.54.155q-.304-.026-.522-.243l-2.42-2.46q-.262-.261-.233-.624q.028-.364.32-.581q1.72-1.266 3.692-1.954q1.972-.69 4.099-.69t4.099.689t3.692 1.954q.292.217.32.58q.03.364-.232.625l-2.421 2.46q-.215.226-.517.247t-.545-.158q-.952-.699-2.074-1.048Q13.2 9.616 12 9.616t-2.322.349m-2.528.15q1.05-.75 2.288-1.124T12 8.616t2.538.362t2.312 1.088l2.2-2.2q-1.55-1.1-3.338-1.675T12 5.616t-3.713.575T4.95 7.866zm4.85 6.27");
}

</style>
