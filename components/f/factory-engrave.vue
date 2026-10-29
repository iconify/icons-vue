<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p12_aet5g.css';
import '../../css/k/ks110b_an.css';
import '../../css/z/z31jlbbvb.css';
import '../../css/n/ngj96acjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p12_aet5g wm-k"/><path class="ks110b_an wm-shadow"/><path class="wm-k z31jlbbvb"/><path class="ngj96acjh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:factory-engrave" /></template>
