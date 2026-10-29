<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tghhffbog.css';
import '../../css/i/i3ovwuonc.css';
import '../../css/k/kllmgpohz.css';
import '../../css/p/ppm0i_bsu.css';
import '../../css/u/u9mj2bo0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tghhffbog"/><path class="i3ovwuonc wm-k"/><path class="kllmgpohz wm-a"/><path class="ppm0i_bsu wm-k"/><path class="u9mj2bo0i wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:house-wifi-sketch" /></template>
