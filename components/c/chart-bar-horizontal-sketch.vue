<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xw_vi2g7o.css';
import '../../css/n/npauvw-9g.css';
import '../../css/c/c16hh-b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-a xw_vi2g7o"/><path class="npauvw-9g wm-k"/><path class="c16hh-b9v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-horizontal-sketch" /></template>
