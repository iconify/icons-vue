<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/q4an57b1a.css';
import '../../css/m/mpw01vvnx.css';
import '../../css/h/hv_jolb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="q4an57b1a"/><path class="mpw01vvnx wm-shadow"/><path class="hv_jolb_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-big-up-engrave" /></template>
