<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdf-683ve.css';
import '../../css/b/bbniaqbna.css';
import '../../css/x/x_zi4lbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGLlWB2cAN" viewBox="0 0 359 231"><path class="wdf-683ve"/></symbol><symbol id="SVGHcBoxeJL" viewBox="0 0 258 66"><path class="bbniaqbna"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-24 0; 24 0; -24 0"/></path><path class="x_zi4lbhl"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="24 0; -24 0; 24 0"/></path></symbol></defs><use width="359" height="231" href="#SVGLlWB2cAN" transform="translate(76.5 140.5)"/><use width="258" height="66" href="#SVGHcBoxeJL" transform="translate(127 405)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:fog" /></template>
