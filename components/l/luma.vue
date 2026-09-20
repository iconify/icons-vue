<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d30_ikb-s.css';
import '../../css/i/i19fo-uuz.css';
import '../../css/t/tim98pa1s.css';
import '../../css/a/azefx4dkv.css';
import '../../css/b/b_kr0oent.css';
import '../../css/d/durztpqia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d30_ikb-s"/><path fill="url(#SVGltE9E56r)" class="i19fo-uuz"/><path fill="url(#SVGltE9E56r)" class="i19fo-uuz"/><path fill="url(#SVGPD4GSdVe)" class="d30_ikb-s"/><path fill="url(#SVGltE9E56r)" class="i19fo-uuz"/><path fill="url(#SVGPD4GSdVe)" class="d30_ikb-s"/><defs><linearGradient id="SVGltE9E56r" x1="2" x2="22.785" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop class="tim98pa1s"/><stop offset="1" class="azefx4dkv"/></linearGradient><linearGradient id="SVGPD4GSdVe" x1="13.748" x2="4.672" y1="22.642" y2="3.745" gradientUnits="userSpaceOnUse"><stop class="b_kr0oent"/><stop offset="1" class="durztpqia"/></linearGradient></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:luma" /></template>
