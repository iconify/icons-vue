<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iqflaeb-i.css';
import '../../css/u/u7w6s54ki.css';
import '../../css/g/gv_0dkbnc.css';
import '../../css/y/yadlqnbvi.css';
import '../../css/n/ntzvg7bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iqflaeb-i"/><path class="u7w6s54ki wm-k"/><path class="gv_0dkbnc wm-s"/><path class="wm-k yadlqnbvi"/><path class="ntzvg7bwe wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-off-sketch" /></template>
