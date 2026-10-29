<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p6__y4b2i.css';
import '../../css/i/ijdo-ebkh.css';
import '../../css/l/ll8gxybws.css';
import '../../css/b/bt4eanb_m.css';
import '../../css/e/ee72xe_hx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p6__y4b2i wm-k"/><path class="ijdo-ebkh wm-a"/><path class="ll8gxybws wm-shadow"/><path class="bt4eanb_m wm-k"/><path class="ee72xe_hx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:building-2-engrave" /></template>
