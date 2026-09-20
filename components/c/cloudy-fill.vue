<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvq0q9f5t.css';
import '../../css/i/iazd5_bwo.css';
import '../../css/g/grny65b5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGMeEfudbH" x1="99.5" x2="232.6" y1="30.7" y2="261.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="yvq0q9f5t"/><stop offset=".5" class="yvq0q9f5t"/><stop offset="1" class="iazd5_bwo"/></linearGradient><symbol id="SVGMnBDAb4I" viewBox="0 0 350 222"><path fill="url(#SVGMeEfudbH)" class="grny65b5z"/></symbol></defs><use width="350" height="222" href="#SVGMnBDAb4I" transform="translate(81 145)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-18 0; 18 0; -18 0"/></use>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:cloudy-fill" /></template>
