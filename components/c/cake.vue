<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vwchn3tyd.css';
import '../../css/c/ctbp2ybpi.css';
import '../../css/v/v3k4esbvy.css';
import '../../css/k/kmhx_lrvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vwchn3tyd"/><path class="ctbp2ybpi"/><circle class="v3k4esbvy"/><path clip-rule="evenodd" class="kmhx_lrvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:cake" /></template>
