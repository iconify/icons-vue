<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e92aedcqx.css';
import '../../css/x/xe2megdde.css';
import '../../css/u/ue6wgg4iq.css';
import '../../css/u/uuu5t1bgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e92aedcqx wm-k"/><path class="wm-a xe2megdde"/><path class="ue6wgg4iq wm-k"/><path class="uuu5t1bgf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-music-sketch" /></template>
