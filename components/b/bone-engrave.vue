<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p1vtcqu8x.css';
import '../../css/v/v8yvcacmt.css';
import '../../css/y/yrnv22bjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p1vtcqu8x"/><path class="v8yvcacmt wm-shadow"/><path class="yrnv22bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bone-engrave" /></template>
