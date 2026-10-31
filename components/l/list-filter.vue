<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sv0c39bkq.css';
import '../../css/o/ot_1jemuk.css';
import '../../css/k/ktix5xn7e.css';
import '../../css/r/rpy3mbs-w.css';
import '../../css/x/xqo1getir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGiMIkUbST" x1="10" x2="14" y1="5" y2="18.99" gradientUnits="userSpaceOnUse"><stop offset="0" class="sv0c39bkq"/><stop offset=".4" class="sv0c39bkq"/><stop offset="1" class="ot_1jemuk"/></linearGradient></defs><path class="ktix5xn7e wm-k"/><path class="rpy3mbs-w wm-deco"/><path fill="url(#SVGiMIkUbST)" class="wm-k xqo1getir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:list-filter" /></template>
