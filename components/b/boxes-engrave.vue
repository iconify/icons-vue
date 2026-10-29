<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tm5umt8cw.css';
import '../../css/k/k11v7xbdk.css';
import '../../css/y/y6iojqb3m.css';
import '../../css/r/r81zoppqz.css';
import '../../css/n/n_2k4vxva.css';
import '../../css/c/c2th96roa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tm5umt8cw"/><path class="k11v7xbdk wm-shadow"/><path class="y6iojqb3m"/><path class="r81zoppqz"/><path class="n_2k4vxva"/><path class="c2th96roa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:boxes-engrave" /></template>
