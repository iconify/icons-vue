<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qh8bn-u7p.css';
import '../../css/h/hz1637bhd.css';
import '../../css/o/o3os9344g.css';
import '../../css/v/v1055zads.css';
import '../../css/u/uv6uwdbji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qh8bn-u7p wm-k"/><path class="hz1637bhd wm-a"/><path class="o3os9344g wm-shadow"/><path class="v1055zads wm-k"/><path class="uv6uwdbji wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-donut-engrave" /></template>
