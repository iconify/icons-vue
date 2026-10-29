<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mj_rm2b7f.css';
import '../../css/i/ig50ogbco.css';
import '../../css/m/m9ebv6big.css';
import '../../css/v/v7jzlzbxs.css';
import '../../css/u/u3s_svo7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mj_rm2b7f wm-k"/><path class="ig50ogbco wm-shadow"/><path class="m9ebv6big wm-k"/><path class="v7jzlzbxs wm-a"/><path class="u3s_svo7g wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-round-engrave" /></template>
