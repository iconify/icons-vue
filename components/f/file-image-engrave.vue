<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sd0xq2bvy.css';
import '../../css/x/xvb7_jbzt.css';
import '../../css/m/mnzbd0b4v.css';
import '../../css/v/vp3_m3b5w.css';
import '../../css/q/qya5idb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sd0xq2bvy wm-k"/><path class="wm-a xvb7_jbzt"/><path class="mnzbd0b4v wm-shadow"/><path class="vp3_m3b5w wm-k"/><path class="qya5idb2k wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-image-engrave" /></template>
