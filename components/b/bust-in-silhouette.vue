<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/feoue7bmd.css';
import '../../css/m/muh3a3bep.css';
import '../../css/l/l7lhxjbaz.css';
import '../../css/j/j4b_e-egk.css';
import '../../css/o/o_5g1sbxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><radialGradient id="SVGB2kB7sCt" cx=".35" cy=".3" r=".8"><stop offset="0" class="feoue7bmd"/><stop offset="1" class="muh3a3bep"/></radialGradient></defs><g fill="url(#SVGB2kB7sCt)" transform="matrix(2.9 0 0 2.9 -31.156 -63.526)" class="l7lhxjbaz"><path class="j4b_e-egk"/><ellipse class="o_5g1sbxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:bust-in-silhouette" /></template>
