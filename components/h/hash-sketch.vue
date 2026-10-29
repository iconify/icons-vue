<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kwb9y2bsn.css';
import '../../css/x/xmya3k2jv.css';
import '../../css/m/mjmnulbuh.css';
import '../../css/j/jczszebcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kwb9y2bsn wm-k"/><path class="wm-a xmya3k2jv"/><path class="mjmnulbuh wm-k"/><path class="jczszebcb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:hash-sketch" /></template>
