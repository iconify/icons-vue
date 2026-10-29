<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jtgxl_ini.css';
import '../../css/l/lyi99rb3b.css';
import '../../css/l/lrkxigbtx.css';
import '../../css/z/z9-ek8f5j.css';
import '../../css/g/g5ykuz3vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jtgxl_ini wm-k"/><path class="lyi99rb3b wm-a"/><path class="lrkxigbtx wm-shadow"/><path class="wm-k z9-ek8f5j"/><path class="g5ykuz3vl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:case-lower-engrave" /></template>
