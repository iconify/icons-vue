<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d4nyqcchx.css';
import '../../css/w/wa2lq1bmf.css';
import '../../css/j/jje4tjgwk.css';
import '../../css/d/dluc55baa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d4nyqcchx"/><path class="wa2lq1bmf wm-a"/><path class="jje4tjgwk wm-k"/><path class="dluc55baa wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-rain-wind-sketch" /></template>
