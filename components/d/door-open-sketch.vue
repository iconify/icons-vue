<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gvmf_2bye.css';
import '../../css/u/up_uepidw.css';
import '../../css/i/ihhg1ni_f.css';
import '../../css/m/m4_wvpbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gvmf_2bye wm-deco"/><path class="up_uepidw wm-k"/><path class="ihhg1ni_f wm-k"/><path class="m4_wvpbdd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:door-open-sketch" /></template>
