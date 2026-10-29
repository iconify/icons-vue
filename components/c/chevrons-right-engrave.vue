<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dtakehbua.css';
import '../../css/f/f0qq2vbkf.css';
import '../../css/q/qnbwq9lbv.css';
import '../../css/b/bnbj9bspw.css';
import '../../css/e/et5-78afr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dtakehbua wm-k"/><path class="f0qq2vbkf wm-a"/><path class="qnbwq9lbv wm-shadow"/><path class="bnbj9bspw wm-k"/><path class="et5-78afr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-right-engrave" /></template>
