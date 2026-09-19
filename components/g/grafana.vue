<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2uek7bnp.css';
import '../../css/e/e4tfsobts.css';
import '../../css/d/dt59drbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGDkkdxczn" x1="45.842" x2="45.842" y1="89.57" y2="8.802" gradientTransform="translate(-2.405 27.316)scale(1.4463)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o2uek7bnp"/><stop offset="1" class="e4tfsobts"/></linearGradient><path fill="url(#SVGDkkdxczn)" class="dt59drbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:grafana" /></template>
