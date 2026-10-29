<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lo1tr_b1c.css';
import '../../css/n/na3rfosvr.css';
import '../../css/j/jgz8mubms.css';
import '../../css/w/w62x13bmw.css';
import '../../css/r/rsai_abhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lo1tr_b1c wm-k"/><path class="na3rfosvr wm-a"/><path class="jgz8mubms wm-shadow"/><path class="w62x13bmw wm-k"/><path class="rsai_abhp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:airplay-engrave" /></template>
