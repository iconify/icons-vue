<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m-x3rzbsa.css';
import '../../css/e/esnzilhjg.css';
import '../../css/m/mxaffh47f.css';
import '../../css/p/pr2-gck8m.css';
import '../../css/x/xrkrxsb1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m-x3rzbsa"/><path class="esnzilhjg wm-k"/><path class="mxaffh47f wm-k"/><path class="pr2-gck8m wm-a"/><path class="wm-a xrkrxsb1e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-column-stacked-sketch" /></template>
