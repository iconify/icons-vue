<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/e4h-h4b2h.css';
import '../../css/j/jchxhzb8n.css';
import '../../css/x/x0gmzy4ai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="e4h-h4b2h"/><path class="jchxhzb8n wm-shadow"/><path class="x0gmzy4ai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-down-engrave" /></template>
