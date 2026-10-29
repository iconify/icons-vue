<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fwjz04bkr.css';
import '../../css/w/wfty0mm_t.css';
import '../../css/y/yr9-fbbjj.css';
import '../../css/x/xvg5t8bzk.css';
import '../../css/p/px00y_byw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fwjz04bkr"/><path class="wfty0mm_t wm-shadow"/><path class="yr9-fbbjj"/><path class="xvg5t8bzk"/><path class="px00y_byw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-teen-engrave" /></template>
