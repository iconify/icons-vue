<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/j55mge9fo.css';
import '../../css/c/cna71lbwk.css';
import '../../css/g/g3r_rtbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="j55mge9fo"/><path class="cna71lbwk"/><path class="g3r_rtbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:filter-close-broken" /></template>
