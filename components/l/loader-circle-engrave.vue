<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ie9ejj3-w.css';
import '../../css/p/pd_04xbwc.css';
import '../../css/a/a88uu03mv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ie9ejj3-w"/><path class="pd_04xbwc wm-shadow"/><path class="a88uu03mv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:loader-circle-engrave" /></template>
