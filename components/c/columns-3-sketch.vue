<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d_pf6lbxf.css';
import '../../css/f/fcut-hbnn.css';
import '../../css/f/fyw5h8ktk.css';
import '../../css/q/qllxogbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d_pf6lbxf"/><path class="fcut-hbnn wm-a"/><path class="fyw5h8ktk wm-k"/><path class="qllxogbek wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:columns-3-sketch" /></template>
