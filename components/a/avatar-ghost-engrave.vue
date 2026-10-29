<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d8limpbps.css';
import '../../css/g/ggc-6abcm.css';
import '../../css/s/siz9glecp.css';
import '../../css/n/nm-qj_bex.css';
import '../../css/k/k05fspbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d8limpbps wm-k"/><path class="ggc-6abcm wm-a"/><path class="siz9glecp wm-shadow"/><path class="nm-qj_bex wm-k"/><path class="k05fspbzc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-ghost-engrave" /></template>
