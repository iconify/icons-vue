<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ema-raczb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fc_9on64f.css';
import '../../css/r/rdsn7pb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ema-raczb secondary"/><g class="dt0cm9dhy primary"><path class="fc_9on64f"/><path class="rdsn7pb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:area-chart-duo" /></template>
