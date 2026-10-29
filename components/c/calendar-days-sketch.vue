<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y1asmybzv.css';
import '../../css/j/jt0ne9b_u.css';
import '../../css/v/vug_eabcd.css';
import '../../css/f/f7unpibui.css';
import '../../css/j/j_h2px3hc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y1asmybzv"/><path class="jt0ne9b_u wm-k"/><path class="vug_eabcd wm-a"/><path class="f7unpibui wm-k"/><path class="j_h2px3hc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-days-sketch" /></template>
