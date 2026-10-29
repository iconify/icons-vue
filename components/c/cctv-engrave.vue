<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vte2xfbes.css';
import '../../css/a/aq-4x7bqm.css';
import '../../css/j/j_29mjbsq.css';
import '../../css/i/ipr557bpu.css';
import '../../css/d/db38wxdje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vte2xfbes wm-k"/><path class="aq-4x7bqm wm-a"/><path class="j_29mjbsq wm-shadow"/><path class="ipr557bpu wm-k"/><path class="db38wxdje wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cctv-engrave" /></template>
