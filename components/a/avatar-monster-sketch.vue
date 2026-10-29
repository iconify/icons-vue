<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qn26cubyt.css';
import '../../css/w/wvox06bua.css';
import '../../css/p/p9nwmabvx.css';
import '../../css/i/i100lfzay.css';
import '../../css/w/wlp156s-x.css';
import '../../css/h/hhksfrbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qn26cubyt wm-k"/><path class="wm-k wvox06bua"/><path class="p9nwmabvx wm-k"/><path class="i100lfzay wm-a"/><path class="wlp156s-x wm-a"/><path class="hhksfrbzl wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-monster-sketch" /></template>
