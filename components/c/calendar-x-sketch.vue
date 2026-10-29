<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nexzb87ke.css';
import '../../css/k/kfmyfx_2h.css';
import '../../css/j/jtyrkbc4a.css';
import '../../css/y/ymnh2gbiy.css';
import '../../css/p/px8c1ob3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nexzb87ke"/><path class="kfmyfx_2h wm-k"/><path class="jtyrkbc4a wm-a"/><path class="wm-k ymnh2gbiy"/><path class="px8c1ob3x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-x-sketch" /></template>
