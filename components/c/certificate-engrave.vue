<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dd23j2bso.css';
import '../../css/m/mxofy6bls.css';
import '../../css/g/gkb_ajwap.css';
import '../../css/c/clwivwvku.css';
import '../../css/w/w09xprbay.css';
import '../../css/w/wtll6dz5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dd23j2bso wm-k"/><path class="mxofy6bls wm-a"/><path class="gkb_ajwap wm-shadow"/><path class="clwivwvku wm-k"/><path class="w09xprbay wm-a"/><path class="wm-a wtll6dz5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:certificate-engrave" /></template>
