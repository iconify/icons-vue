<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rjhr_yfqp.css';
import '../../css/w/w0tahgb7o.css';
import '../../css/u/un6g0p8cw.css';
import '../../css/f/fjtiwkodd.css';
import '../../css/u/u2-g4hbgt.css';
import '../../css/d/dt5qoccsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rjhr_yfqp"/><path class="w0tahgb7o wm-shadow"/><path class="un6g0p8cw"/><path class="fjtiwkodd"/><path class="u2-g4hbgt"/><path class="dt5qoccsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:gold-ingot-engrave" /></template>
