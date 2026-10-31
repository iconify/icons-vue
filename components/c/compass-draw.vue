<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/y31pqv8_y.css';
import '../../css/m/mxyavg57n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="y31pqv8_y"><animate fill="freeze" attributeName="opacity" dur="0.12s" values="0;1"/><animate fill="freeze" attributeName="stroke-dashoffset" calcMode="spline" dur="0.5s" keySplines="0.65 0 0.35 1" keyTimes="0;1" values="62.21;0"/></circle><g opacity=".5"><path class="mxyavg57n"><animate fill="freeze" attributeName="opacity" dur="0.2s" keyTimes="0;0.4;1" values="0;0;1"/><animate fill="freeze" attributeName="stroke-dashoffset" calcMode="spline" dur="0.58s" keySplines="0 0 1 1;0.65 0 0.35 1" keyTimes="0;0.138;1" values="24.27;24.27;0"/></path></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:compass-draw" /></template>
