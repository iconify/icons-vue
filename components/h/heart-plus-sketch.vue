<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g_3c4xboi.css';
import '../../css/t/t201aeb7o.css';
import '../../css/p/pymwtrb1e.css';
import '../../css/t/t_h-3qd1c.css';
import '../../css/v/vmrq-dbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g_3c4xboi"/><path class="t201aeb7o wm-k"/><path class="pymwtrb1e wm-s"/><path class="t_h-3qd1c wm-k"/><path class="vmrq-dbxi wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-plus-sketch" /></template>
