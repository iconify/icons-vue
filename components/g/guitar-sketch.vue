<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yfi9mw0on.css';
import '../../css/j/js1cg8hhl.css';
import '../../css/h/hg4aqjb-i.css';
import '../../css/s/srq0_1iwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yfi9mw0on"/><path class="js1cg8hhl wm-a"/><path class="hg4aqjb-i wm-k"/><path class="srq0_1iwc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:guitar-sketch" /></template>
