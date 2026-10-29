<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/a7ig7gbdc.css';
import '../../css/x/x5lnnybdj.css';
import '../../css/i/iy9d3l7td.css';
import '../../css/q/q0yce_brc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="a7ig7gbdc wm-k"/><path class="wm-a x5lnnybdj"/><path class="iy9d3l7td wm-k"/><path class="q0yce_brc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-man-cap-sketch" /></template>
