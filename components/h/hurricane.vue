<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv-71ub5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pv-71ub5e"><animateTransform additive="sum" attributeName="transform" dur="6s" repeatCount="indefinite" type="rotate" values="1440 256 256; 0 256 256"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:hurricane" /></template>
