<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p4loazbkt.css';
import '../../css/v/v61sqybyj.css';
import '../../css/i/i5h3wzb6z.css';
import '../../css/w/wohwviwqc.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p4loazbkt wm-shadow"/><path class="v61sqybyj wm-k"/><path class="i5h3wzb6z wm-k"/><path class="wm-k wohwviwqc"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:lightbulb-off-engrave" /></template>
