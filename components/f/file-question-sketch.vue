<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/ker56obyj.css';
import '../../css/b/bqch6nb3d.css';
import '../../css/g/gxcr2mbxo.css';
import '../../css/g/g077gccan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ker56obyj"/><path class="bqch6nb3d wm-a"/><path class="gxcr2mbxo wm-k"/><path class="g077gccan wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-question-sketch" /></template>
