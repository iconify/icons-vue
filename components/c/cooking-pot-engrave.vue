<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ierrpibnk.css';
import '../../css/m/mzn8-sbvw.css';
import '../../css/x/xg9zu_abp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ierrpibnk"/><path class="mzn8-sbvw wm-shadow"/><path class="xg9zu_abp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cooking-pot-engrave" /></template>
