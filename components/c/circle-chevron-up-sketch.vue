<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xzizubbgh.css';
import '../../css/n/n5bw5rb1s.css';
import '../../css/v/vd_sncc5p.css';
import '../../css/p/pui78qb2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xzizubbgh"/><path class="n5bw5rb1s wm-a"/><path class="vd_sncc5p wm-k"/><path class="pui78qb2p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-up-sketch" /></template>
