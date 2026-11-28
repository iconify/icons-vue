<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/if_fr7tub.css';
import '../../css/d/dd77q5buj.css';
import '../../css/u/udn08f86y.css';
import '../../css/z/z_rx2jgli.css';
import '../../css/h/ht09lzbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="if_fr7tub"/><path class="dd77q5buj"/><path class="udn08f86y"/><path class="z_rx2jgli"/><path class="ht09lzbeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chart-candlestick" /></template>
