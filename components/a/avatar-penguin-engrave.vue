<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/ncrc9rbrr.css';
import '../../css/l/lowswlbbm.css';
import '../../css/e/ewou_cb1d.css';
import '../../css/w/wpx2v_c8k.css';
import '../../css/k/k1xf4_bso.css';
import '../../css/u/ukf9b-bih.css';
import '../../css/w/w6m20q1nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ncrc9rbrr wm-k"/><path class="lowswlbbm wm-shadow"/><path class="ewou_cb1d wm-k"/><path class="wm-k wpx2v_c8k"/><path class="k1xf4_bso wm-a"/><path class="ukf9b-bih wm-k"/><path class="w6m20q1nx wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-penguin-engrave" /></template>
