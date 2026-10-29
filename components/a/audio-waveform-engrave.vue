<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/h8xub9bvx.css';
import '../../css/u/u94jc6b_g.css';
import '../../css/a/a_y8s9b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="h8xub9bvx"/><path class="u94jc6b_g wm-shadow"/><path class="a_y8s9b1k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:audio-waveform-engrave" /></template>
