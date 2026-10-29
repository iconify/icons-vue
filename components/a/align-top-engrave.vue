<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vepu0acja.css';
import '../../css/p/pgts_fbig.css';
import '../../css/w/w5fegjbui.css';
import '../../css/w/wj05nbxlz.css';
import '../../css/g/g4o146b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vepu0acja wm-k"/><path class="pgts_fbig wm-a"/><path class="w5fegjbui wm-shadow"/><path class="wj05nbxlz wm-k"/><path class="g4o146b6z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:align-top-engrave" /></template>
