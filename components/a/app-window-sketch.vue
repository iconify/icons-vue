<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jtpswu7ak.css';
import '../../css/m/mvkcupbgs.css';
import '../../css/u/u_6g3bbkk.css';
import '../../css/c/caxef8g7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jtpswu7ak"/><path class="mvkcupbgs wm-k"/><path class="u_6g3bbkk wm-k"/><path class="caxef8g7p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:app-window-sketch" /></template>
