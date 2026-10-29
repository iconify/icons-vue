<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y51shub2s.css';
import '../../css/q/qxwv1nbma.css';
import '../../css/l/l5bot_fnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y51shub2s"/><path class="qxwv1nbma wm-shadow"/><path class="l5bot_fnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:filter-engrave" /></template>
