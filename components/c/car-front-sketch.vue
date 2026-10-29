<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lg_nejb3d.css';
import '../../css/x/xnz7p-bku.css';
import '../../css/h/hbuj9d8ju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lg_nejb3d wm-k"/><path class="wm-k xnz7p-bku"/><path class="hbuj9d8ju wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:car-front-sketch" /></template>
