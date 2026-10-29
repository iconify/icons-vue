<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qsw3yebfy.css';
import '../../css/c/cc7rpwbsq.css';
import '../../css/x/xfnzpgbvh.css';
import '../../css/p/pandr5r4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qsw3yebfy"/><path class="cc7rpwbsq wm-shadow"/><path class="xfnzpgbvh"/><path class="pandr5r4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bamboo-engrave" /></template>
