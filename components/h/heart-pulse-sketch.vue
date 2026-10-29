<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/ns06ew8yj.css';
import '../../css/y/yajyyvbsx.css';
import '../../css/f/fjo69vb2a.css';
import '../../css/n/nole5l7ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ns06ew8yj wm-k"/><path class="wm-k yajyyvbsx"/><path class="fjo69vb2a wm-k"/><path class="nole5l7ip wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-pulse-sketch" /></template>
