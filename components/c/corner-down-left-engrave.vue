<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tx07i-bgb.css';
import '../../css/q/qv2zs89mx.css';
import '../../css/i/i8wqk5bpm.css';
import '../../css/m/m1x9aqbbi.css';
import '../../css/n/nzf69t93l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tx07i-bgb wm-k"/><path class="qv2zs89mx wm-a"/><path class="i8wqk5bpm wm-shadow"/><path class="m1x9aqbbi wm-k"/><path class="nzf69t93l wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-down-left-engrave" /></template>
