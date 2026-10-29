<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f0jo1sayc.css';
import '../../css/m/mp2an_e3g.css';
import '../../css/n/nd_fneb4o.css';
import '../../css/j/jlp-ovbkm.css';
import '../../css/w/wm1y2mbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f0jo1sayc wm-k"/><path class="mp2an_e3g wm-a"/><path class="nd_fneb4o wm-shadow"/><path class="jlp-ovbkm wm-k"/><path class="wm-a wm1y2mbyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-circuit-engrave" /></template>
