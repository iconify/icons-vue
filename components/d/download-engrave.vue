<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z4cu88gpg.css';
import '../../css/v/vrnnnjbra.css';
import '../../css/e/e6k4xt8_u.css';
import '../../css/l/lw875-p4x.css';
import '../../css/y/yohw-bcjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z4cu88gpg"/><path class="vrnnnjbra wm-a"/><path class="e6k4xt8_u wm-shadow"/><path class="lw875-p4x wm-k"/><path class="wm-a yohw-bcjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:download-engrave" /></template>
