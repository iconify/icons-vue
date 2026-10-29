<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lwtp4nbgu.css';
import '../../css/d/d-j-3vbzo.css';
import '../../css/w/wanqtl7hh.css';
import '../../css/k/kn3piikji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lwtp4nbgu wm-k"/><path class="d-j-3vbzo wm-a"/><path class="wanqtl7hh wm-k"/><path class="kn3piikji wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-line-sketch" /></template>
