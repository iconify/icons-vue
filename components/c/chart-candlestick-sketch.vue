<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/etzt8li8p.css';
import '../../css/l/lv9qmw66s.css';
import '../../css/q/q0mlcsbte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="etzt8li8p wm-a"/><path class="lv9qmw66s wm-k"/><path class="q0mlcsbte wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-candlestick-sketch" /></template>
