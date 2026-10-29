<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pe_q0p22f.css';
import '../../css/c/cjljwz1fs.css';
import '../../css/r/r9clafb6t.css';
import '../../css/n/nwhtk883n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pe_q0p22f"/><path class="cjljwz1fs wm-a"/><path class="r9clafb6t wm-k"/><path class="nwhtk883n wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:kanban-sketch" /></template>
