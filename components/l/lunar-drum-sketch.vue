<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hukkl55px.css';
import '../../css/w/w4o_mqs1s.css';
import '../../css/a/a4drb_btg.css';
import '../../css/q/qe7bs-blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hukkl55px wm-a"/><path class="w4o_mqs1s wm-k"/><path class="a4drb_btg wm-a"/><path class="qe7bs-blu wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lunar-drum-sketch" /></template>
