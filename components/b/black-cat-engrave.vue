<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eb3udlcqj.css';
import '../../css/g/gq5aybb5j.css';
import '../../css/q/qg-00dxjb.css';
import '../../css/w/w0f6d_bws.css';
import '../../css/w/w27peibbj.css';
import '../../css/i/ivddysb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eb3udlcqj wm-k"/><path class="gq5aybb5j wm-a"/><path class="qg-00dxjb wm-shadow"/><path class="w0f6d_bws wm-k"/><path class="w27peibbj wm-a"/><path class="ivddysb5x wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:black-cat-engrave" /></template>
