<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yt_9kfb3y.css';
import '../../css/e/e_2r2m0ir.css';
import '../../css/o/owvr77b1a.css';
import '../../css/u/uaae7209v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yt_9kfb3y"/><path class="e_2r2m0ir wm-k"/><path class="owvr77b1a wm-k"/><path class="uaae7209v wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bot-message-square-sketch" /></template>
