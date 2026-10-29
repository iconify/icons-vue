<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h805s_bny.css';
import '../../css/q/qm565hbxw.css';
import '../../css/x/xg34h7wbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h805s_bny"/><path class="qm565hbxw wm-k"/><path class="wm-a xg34h7wbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hexagon-sketch" /></template>
