<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u_anthadu.css';
import '../../css/p/p1zj69bwt.css';
import '../../css/w/w5y8lebkd.css';
import '../../css/a/a0j3l762m.css';
import '../../css/q/qum0vnbsk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u_anthadu wm-k"/><path class="p1zj69bwt wm-a"/><path class="w5y8lebkd wm-shadow"/><path class="a0j3l762m wm-k"/><path class="qum0vnbsk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-up-left-engrave" /></template>
