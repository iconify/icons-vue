<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m3dedbbyn.css';
import '../../css/o/ods51qbhy.css';
import '../../css/x/x2chrcbtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m3dedbbyn"/><path class="ods51qbhy wm-k"/><path class="wm-a x2chrcbtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:donut-sketch" /></template>
