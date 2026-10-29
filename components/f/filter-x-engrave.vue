<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f_hoxjmun.css';
import '../../css/f/f6jryfoml.css';
import '../../css/s/s8lza-b-b.css';
import '../../css/s/s0uk8_bdj.css';
import '../../css/f/f9b4d59gs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f_hoxjmun wm-k"/><path class="f6jryfoml wm-s"/><path class="s8lza-b-b wm-shadow"/><path class="s0uk8_bdj wm-k"/><path class="f9b4d59gs wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:filter-x-engrave" /></template>
