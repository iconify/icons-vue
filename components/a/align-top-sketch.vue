<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bvyhanbhw.css';
import '../../css/g/gk6fuqrcf.css';
import '../../css/q/qpnl1sbkh.css';
import '../../css/q/q2pcxvj8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bvyhanbhw"/><path class="gk6fuqrcf wm-k"/><path class="qpnl1sbkh wm-k"/><path class="q2pcxvj8p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-top-sketch" /></template>
