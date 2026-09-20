<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlp_fac0s.css';
import '../../css/l/lggn3pbqj.css';
import '../../css/i/it_4m_rqw.css';
import '../../css/u/ufxtx8mph.css';
import '../../css/q/q6r1i_bko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":224};
const content = `<defs><linearGradient id="SVGssQ2Xbjz" x1="-6.452%" x2="85.236%" y1="49.784%" y2="49.784%"><stop offset="0%" class="vlp_fac0s"/><stop offset="100%" class="lggn3pbqj"/></linearGradient><linearGradient id="SVGFlaRCblf" x1="106.079%" x2="14.268%" y1="49.784%" y2="49.784%"><stop offset="0%" class="vlp_fac0s"/><stop offset="100%" class="lggn3pbqj"/></linearGradient><linearGradient id="SVGru2OOiqc" x1="-12.871%" x2="169.796%" y1="75.863%" y2="74.878%"><stop offset="0%" class="vlp_fac0s"/><stop offset="100%" class="lggn3pbqj"/></linearGradient></defs><path fill="url(#SVGssQ2Xbjz)" class="it_4m_rqw"/><path fill="url(#SVGFlaRCblf)" class="ufxtx8mph"/><path fill="url(#SVGru2OOiqc)" class="q6r1i_bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gradio" /></template>
