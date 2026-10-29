<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oa29y7bly.css';
import '../../css/x/x953aub5i.css';
import '../../css/m/mtbeuljrv.css';
import '../../css/q/qb8r96btl.css';
import '../../css/b/bry1z00iu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oa29y7bly wm-k"/><path class="wm-a x953aub5i"/><path class="mtbeuljrv wm-shadow"/><path class="qb8r96btl wm-k"/><path class="bry1z00iu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-ordered-engrave" /></template>
