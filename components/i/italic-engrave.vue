<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/es-93ttzx.css';
import '../../css/h/h0a4pacnc.css';
import '../../css/k/k-_um54tc.css';
import '../../css/b/buvuav6_l.css';
import '../../css/y/y9asu80_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="es-93ttzx wm-k"/><path class="h0a4pacnc wm-a"/><path class="k-_um54tc wm-shadow"/><path class="buvuav6_l wm-k"/><path class="wm-a y9asu80_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:italic-engrave" /></template>
