<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bv7x1rpjr.css';
import '../../css/i/ii6a5nb_d.css';
import '../../css/h/hczd6go5r.css';
import '../../css/w/wwtrsbcvy.css';
import '../../css/b/bhy4-61wh.css';
import '../../css/i/iwu-0yrln.css';
import '../../css/k/kyiupabxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bv7x1rpjr wm-k"/><path class="ii6a5nb_d wm-a"/><path class="hczd6go5r wm-s"/><path class="wm-shadow wwtrsbcvy"/><path class="bhy4-61wh wm-k"/><path class="iwu-0yrln wm-a"/><path class="kyiupabxi wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flip-horizontal-engrave" /></template>
