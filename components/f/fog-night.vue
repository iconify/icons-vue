<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfjgl05hi.css';
import '../../css/b/bbniaqbna.css';
import '../../css/x/x_zi4lbhl.css';
import '../../css/t/tjdecabze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGG3UcUlWO" viewBox="0 0 279 279"><path class="zfjgl05hi"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="-15 135 135; 9 135 135; -15 135 135"/></path></symbol><symbol id="SVGHcBoxeJL" viewBox="0 0 258 66"><path class="bbniaqbna"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="-24 0; 24 0; -24 0"/></path><path class="x_zi4lbhl"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="translate" values="24 0; -24 0; 24 0"/></path></symbol><clipPath id="SVGWfBvnzCF"><path class="tjdecabze"/></clipPath></defs><g clip-path="url(#SVGWfBvnzCF)"><use width="279" height="279" href="#SVGG3UcUlWO" transform="translate(116.5 116.5)"/></g><use width="258" height="66" href="#SVGHcBoxeJL" transform="translate(127 339)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:fog-night" /></template>
