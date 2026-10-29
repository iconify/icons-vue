<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xyuyjnbmb.css';
import '../../css/x/xf879kbtn.css';
import '../../css/x/xb6o97btl.css';
import '../../css/k/k5csy4bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k xyuyjnbmb"/><path class="wm-a xf879kbtn"/><path class="wm-k xb6o97btl"/><path class="k5csy4bbb wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:airplay-sketch" /></template>
