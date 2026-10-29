<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cgzrd6bda.css';
import '../../css/v/vk17_kbpb.css';
import '../../css/k/kwicdkbyg.css';
import '../../css/d/dy6f-b0he.css';
import '../../css/d/djl3n2rtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cgzrd6bda wm-k"/><path class="vk17_kbpb wm-a"/><path class="kwicdkbyg wm-shadow"/><path class="dy6f-b0he wm-k"/><path class="djl3n2rtw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cup-soda-engrave" /></template>
