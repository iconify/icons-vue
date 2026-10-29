<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mm-gt2b9k.css';
import '../../css/y/yu89iabdp.css';
import '../../css/k/k8n73abrs.css';
import '../../css/h/hbjcd_klt.css';
import '../../css/v/vpx65vhyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mm-gt2b9k wm-deco"/><path class="wm-k yu89iabdp"/><path class="k8n73abrs wm-k"/><path class="hbjcd_klt wm-a"/><path class="vpx65vhyy wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lasso-sketch" /></template>
