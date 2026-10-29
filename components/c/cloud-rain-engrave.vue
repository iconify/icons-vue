<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_jv868wi.css';
import '../../css/u/uyg_llr-r.css';
import '../../css/h/h13gbmb1u.css';
import '../../css/l/lhr7mp78x.css';
import '../../css/d/dwntyeyxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_jv868wi wm-k"/><path class="uyg_llr-r wm-a"/><path class="h13gbmb1u wm-shadow"/><path class="lhr7mp78x wm-k"/><path class="dwntyeyxt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cloud-rain-engrave" /></template>
