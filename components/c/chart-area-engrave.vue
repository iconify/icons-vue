<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yrhaee07g.css';
import '../../css/i/i8ycrbbjm.css';
import '../../css/l/lvjvbab4v.css';
import '../../css/c/cw36_6mco.css';
import '../../css/g/gzms0bb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k yrhaee07g"/><path class="i8ycrbbjm wm-a"/><path class="lvjvbab4v wm-shadow"/><path class="cw36_6mco wm-a"/><path class="gzms0bb9f wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-area-engrave" /></template>
