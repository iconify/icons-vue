<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mc_ly-npi.css';
import '../../css/m/mrzjofi4h.css';
import '../../css/t/tp23o5cae.css';
import '../../css/t/t99xelbnc.css';
import '../../css/k/k4othtbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mc_ly-npi wm-k"/><path class="mrzjofi4h wm-a"/><path class="tp23o5cae wm-shadow"/><path class="t99xelbnc wm-k"/><path class="k4othtbmn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-open-engrave" /></template>
