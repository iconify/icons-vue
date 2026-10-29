<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c5xgsv_dp.css';
import '../../css/r/rvwqm3q_x.css';
import '../../css/w/w74ukmbki.css';
import '../../css/p/p8jzkvbki.css';
import '../../css/w/wbow0vbca.css';
import '../../css/o/oe5vmrb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c5xgsv_dp wm-k"/><path class="rvwqm3q_x wm-a"/><path class="w74ukmbki wm-shadow"/><path class="p8jzkvbki wm-k"/><path class="wbow0vbca wm-a"/><path class="oe5vmrb1n wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:crystal-ball-engrave" /></template>
