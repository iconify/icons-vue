<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yylgmr2nv.css';
import '../../css/y/yvj11htlz.css';
import '../../css/g/glhzmfa1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yylgmr2nv"/><path class="yvj11htlz"/><path class="glhzmfa1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:covid19-virus-heal-2" /></template>
