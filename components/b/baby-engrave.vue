<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/seejxhb6k.css';
import '../../css/u/uisobyeyf.css';
import '../../css/w/wc_hv_34n.css';
import '../../css/y/y23w8kzbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="seejxhb6k"/><path class="uisobyeyf wm-shadow"/><path class="wc_hv_34n"/><path class="y23w8kzbh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baby-engrave" /></template>
