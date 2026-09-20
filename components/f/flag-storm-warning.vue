<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7zi9bkg.css';
import '../../css/a/a4l89jl3b.css';
import '../../css/e/eq6phunxa.css';
import '../../css/m/mthzp357c.css';
import '../../css/m/mcqnoxpmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGPOegQkok" x1="116.5" x2="232.5" y1="155.6" y2="356.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="te7zi9bkg"/><stop offset=".5" class="te7zi9bkg"/><stop offset="1" class="a4l89jl3b"/></linearGradient></defs><path stroke="url(#SVGPOegQkok)" class="eq6phunxa"/><g><rect class="mthzp357c"/><rect class="mcqnoxpmx"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="scale" values="1 1; 1.1 1; 1 1"/><animateTransform additive="sum" attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1" repeatCount="indefinite" type="translate" values="0 0; -18 0; 0 0"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:flag-storm-warning" /></template>
