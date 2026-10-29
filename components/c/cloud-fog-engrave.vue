<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_jv868wi.css';
import '../../css/s/sw1e5_zio.css';
import '../../css/o/oags8zbjj.css';
import '../../css/l/lhr7mp78x.css';
import '../../css/a/al_hgmb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_jv868wi wm-k"/><path class="sw1e5_zio wm-a"/><path class="oags8zbjj wm-shadow"/><path class="lhr7mp78x wm-k"/><path class="al_hgmb2q wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-fog-engrave" /></template>
