<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/w72h1h5zq.css';
import '../../css/h/hf2cx4ppo.css';
import '../../css/n/n37qylb6g.css';
import '../../css/l/lh_y89hot.css';
import '../../css/t/tjlpedbiu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="w72h1h5zq wm-k"/><path class="hf2cx4ppo wm-a"/><path class="n37qylb6g wm-shadow"/><path class="lh_y89hot wm-k"/><path class="tjlpedbiu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:holly-engrave" /></template>
