<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g6gf1kiut.css';
import '../../css/q/qia-1etpx.css';
import '../../css/l/lt97xvblj.css';
import '../../css/b/bov66nrpl.css';
import '../../css/h/hfi5e-rtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g6gf1kiut wm-k"/><path class="qia-1etpx wm-a"/><path class="lt97xvblj wm-shadow"/><path class="bov66nrpl wm-k"/><path class="hfi5e-rtf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:list-engrave" /></template>
