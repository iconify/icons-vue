<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uvnqbw1ky.css';
import '../../css/e/e2vntlx_k.css';
import '../../css/t/tavb7nbpf.css';
import '../../css/s/s-orxf9cs.css';
import '../../css/z/z-jqc1b6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uvnqbw1ky wm-k"/><path class="e2vntlx_k wm-a"/><path class="tavb7nbpf wm-shadow"/><path class="s-orxf9cs wm-a"/><path class="wm-k z-jqc1b6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:arrow-right-to-line-engrave" /></template>
