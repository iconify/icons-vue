<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rvnfwdfds.css';
import '../../css/s/scp0tkbbg.css';
import '../../css/d/dtbxyvb-n.css';
import '../../css/y/ynl6k533e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rvnfwdfds"/><path class="scp0tkbbg wm-a"/><path class="dtbxyvb-n wm-k"/><path class="wm-a ynl6k533e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:file-chart-sketch" /></template>
