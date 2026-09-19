<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fn7sfubln.css';
import '../../css/w/wqv4fibjt.css';
import '../../css/h/hppgl373x.css';
import '../../css/a/aqkliebgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fn7sfubln"/><path clip-rule="evenodd" class="wqv4fibjt"/><path class="hppgl373x"/><path clip-rule="evenodd" class="aqkliebgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:box-layout-4-duo" /></template>
