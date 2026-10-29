<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mt2qoyrju.css';
import '../../css/t/tc_n04vxp.css';
import '../../css/n/n2fikpbkb.css';
import '../../css/p/pnrbgxb5c.css';
import '../../css/k/k6q1i4brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mt2qoyrju wm-k"/><path class="tc_n04vxp wm-a"/><path class="n2fikpbkb wm-shadow"/><path class="pnrbgxb5c wm-a"/><path class="k6q1i4brf wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:broom-engrave" /></template>
