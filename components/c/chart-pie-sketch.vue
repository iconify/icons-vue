<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tdg802bof.css';
import '../../css/y/ykh49b9ke.css';
import '../../css/t/tk0lgzf0i.css';
import '../../css/r/r6h4jfbmd.css';
import '../../css/n/nvxnz7uds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tdg802bof"/><path class="wm-k ykh49b9ke"/><path class="tk0lgzf0i wm-a"/><path class="r6h4jfbmd wm-k"/><path class="nvxnz7uds wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-pie-sketch" /></template>
