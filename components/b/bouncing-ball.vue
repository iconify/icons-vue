<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zel9kubnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse cy="5" rx="4" ry="4" class="zel9kubnb"><animate id="SVG2g6X4cnm" fill="freeze" attributeName="cy" begin="0;SVGYUW1Wdmy.end" calcMode="spline" dur="0.375s" keySplines=".33,0,.66,.33" values="5;20"/><animate attributeName="rx" begin="SVG2g6X4cnm.end" calcMode="spline" dur="0.05s" keySplines=".33,0,.66,.33;.33,.66,.66,1" values="4;4.8;4"/><animate attributeName="ry" begin="SVG2g6X4cnm.end" calcMode="spline" dur="0.05s" keySplines=".33,0,.66,.33;.33,.66,.66,1" values="4;3;4"/><animate id="SVGb9s1Jd3o" attributeName="cy" begin="SVG2g6X4cnm.end" calcMode="spline" dur="0.025s" keySplines=".33,0,.66,.33" values="20;20.5"/><animate id="SVGYUW1Wdmy" attributeName="cy" begin="SVGb9s1Jd3o.end" calcMode="spline" dur="0.4s" keySplines=".33,.66,.66,1" values="20.5;5"/></ellipse>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="svg-spinners:bouncing-ball" /></template>
