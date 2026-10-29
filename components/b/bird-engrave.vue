<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xvjrys-1s.css';
import '../../css/x/xtz53xfqp.css';
import '../../css/f/fo_32oblh.css';
import '../../css/q/qz-3_0bjm.css';
import '../../css/z/z0orz_bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xvjrys-1s"/><path class="wm-a xtz53xfqp"/><path class="fo_32oblh wm-shadow"/><path class="qz-3_0bjm wm-k"/><path class="wm-a z0orz_bkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bird-engrave" /></template>
