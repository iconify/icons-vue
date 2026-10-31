<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv0c39bkq.css';
import '../../css/o/ot_1jemuk.css';
import '../../css/m/mu98ifbwt.css';
import '../../css/v/v82w1lb6a.css';
import '../../css/t/tvh2ncl-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGZyvXocOT" x1="10.75" x2="14.75" y1="3.51" y2="18.5" gradientUnits="userSpaceOnUse"><stop offset="0" class="sv0c39bkq"/><stop offset=".4" class="sv0c39bkq"/><stop offset="1" class="ot_1jemuk"/></linearGradient></defs><path class="mu98ifbwt wm-k"/><path class="v82w1lb6a wm-deco"/><path fill="url(#SVGZyvXocOT)" class="tvh2ncl-m wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:jalebi" /></template>
