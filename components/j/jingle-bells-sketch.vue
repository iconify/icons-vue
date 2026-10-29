<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xc9kxsl1e.css';
import '../../css/z/z0l1z5b1x.css';
import '../../css/x/x4md61b4h.css';
import '../../css/q/q7ta1gemp.css';
import '../../css/z/zycozjbot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xc9kxsl1e"/><path class="wm-a z0l1z5b1x"/><path class="wm-k x4md61b4h"/><path class="q7ta1gemp wm-a"/><path class="wm-s zycozjbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:jingle-bells-sketch" /></template>
