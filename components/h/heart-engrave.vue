<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m_-dhfbtd.css';
import '../../css/h/hanoadvko.css';
import '../../css/u/uh01hzbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m_-dhfbtd"/><path class="hanoadvko wm-shadow"/><path class="uh01hzbyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-engrave" /></template>
