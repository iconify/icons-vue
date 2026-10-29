<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oxa8kyfga.css';
import '../../css/j/jvw0w5byh.css';
import '../../css/v/vghekgbcn.css';
import '../../css/i/izx2oobri.css';
import '../../css/u/u8_zcib_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oxa8kyfga wm-k"/><path class="jvw0w5byh wm-a"/><path class="vghekgbcn wm-shadow"/><path class="izx2oobri wm-k"/><path class="u8_zcib_q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-down-right-engrave" /></template>
