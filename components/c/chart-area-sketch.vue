<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/ngezjftiy.css';
import '../../css/v/vbakllcin.css';
import '../../css/j/j1rrsfb2p.css';
import '../../css/g/g3cpwtupq.css';
import '../../css/f/ff8ix3a1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ngezjftiy wm-a"/><path class="vbakllcin wm-k"/><path class="j1rrsfb2p wm-k"/><path class="g3cpwtupq wm-a"/><path class="ff8ix3a1v wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-area-sketch" /></template>
