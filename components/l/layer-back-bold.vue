<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oze6jsybx.css';
import '../../css/z/zu_amvtay.css';
import '../../css/m/mqm_betay.css';
import '../../css/y/yano2qblk.css';
import '../../css/h/hrnojc6mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="oze6jsybx"/><path clip-rule="evenodd" class="zu_amvtay"/><path class="mqm_betay"/><path clip-rule="evenodd" class="yano2qblk"/><path class="hrnojc6mh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-back-bold" /></template>
