<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fqk8mibcy.css';
import '../../css/y/yfymn2bvd.css';
import '../../css/a/a7bdy2bmd.css';
import '../../css/j/jz3_6ebnd.css';
import '../../css/j/jh_711eur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGW5DxpeQV" x1="9" x2="15" y1="5" y2="21.99" gradientUnits="userSpaceOnUse"><stop offset="0" class="fqk8mibcy"/><stop offset="1" class="yfymn2bvd"/></linearGradient></defs><path fill="url(#SVGW5DxpeQV)" class="a7bdy2bmd"/><path class="jz3_6ebnd wm-s"/><path class="jh_711eur wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-utsav:list-plus" /></template>
