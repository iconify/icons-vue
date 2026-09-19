<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/ohm435bso.css';
import '../../css/o/oorsanbvf.css';
import '../../css/l/le9kjkvqq.css';
import '../../css/l/lnv51_btx.css';
import '../../css/o/odikd2brz.css';
import '../../css/k/kvzy8wbjh.css';
import '../../css/l/lle4zh-ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="ohm435bso"/><path class="oorsanbvf"/><path class="le9kjkvqq"/><path class="lnv51_btx"/><path class="odikd2brz"/><path class="kvzy8wbjh"/><path class="lle4zh-ia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:dialogflow-insights" /></template>
