<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cjpm2ubos.css';
import '../../css/w/wghzogpwq.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/c/csqjp7bsh.css';
import '../../css/l/lcou3abui.css';
import '../../css/o/op1x1ovuv.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cjpm2ubos wm-k"/><path class="wghzogpwq wm-a"/><path class="ol-kpp5cg wm-s"/><path class="csqjp7bsh wm-shadow"/><path class="lcou3abui wm-k"/><path class="op1x1ovuv wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flag-off-engrave" /></template>
