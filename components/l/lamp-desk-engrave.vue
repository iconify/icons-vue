<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/prnexjb1i.css';
import '../../css/r/rvo8e2pwf.css';
import '../../css/l/lx6vztc2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="prnexjb1i"/><path class="rvo8e2pwf wm-shadow"/><path class="lx6vztc2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lamp-desk-engrave" /></template>
