<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ci35hacss.css';
import '../../css/f/fzy7xu4pc.css';
import '../../css/m/m3y59dfla.css';
import '../../css/l/llod8s1is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ci35hacss wm-k"/><path class="fzy7xu4pc wm-shadow"/><path class="m3y59dfla wm-k"/><path class="llod8s1is wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:alert-triangle-engrave" /></template>
