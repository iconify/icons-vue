<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ah2nw_bsy.css';
import '../../css/l/lpkhpnbrd.css';
import '../../css/g/g_3ckc6_n.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/x/x2uudub6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ah2nw_bsy wm-k"/><path class="lpkhpnbrd wm-a"/><path class="g_3ckc6_n wm-shadow"/><path class="wm-k yw4fz_b6b"/><path class="wm-a x2uudub6d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:basketball-engrave" /></template>
