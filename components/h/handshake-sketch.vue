<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t3fmph07q.css';
import '../../css/z/zed8uz8yd.css';
import '../../css/e/exdiltbqb.css';
import '../../css/r/rjtu802pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t3fmph07q wm-k"/><path class="wm-a zed8uz8yd"/><path class="exdiltbqb wm-k"/><path class="rjtu802pw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:handshake-sketch" /></template>
