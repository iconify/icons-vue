<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdf-683ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGLlWB2cAN" viewBox="0 0 359 231"><path class="wdf-683ve"/></symbol></defs><use width="359" height="231" href="#SVGLlWB2cAN" transform="translate(76.5 140.5)"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-18 0; 18 0; -18 0"/></use>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:cloudy" /></template>
