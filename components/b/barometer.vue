<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybf6b_bce.css';
import '../../css/g/gr9vblbwk.css';
import '../../css/o/o_5gryb3v.css';
import '../../css/l/ljac3j5dx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ybf6b_bce"/><path class="gr9vblbwk"/><circle class="o_5gryb3v"/><path class="ljac3j5dx"><animateTransform attributeName="transform" calcMode="spline" dur="6s" keySplines=".42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1; .42, 0, .58, 1" keyTimes="0; .17; .25; .42; .5; .67; 1" repeatCount="indefinite" type="rotate" values="-54 256 256; -15 256 256; -36 256 256; 36 256 256; 10 256 256; 115 256 256; -54 256 256"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:barometer" /></template>
