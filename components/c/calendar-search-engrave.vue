<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mae_raf5q.css';
import '../../css/j/jalfqco1n.css';
import '../../css/l/lmvq19bdy.css';
import '../../css/d/dlyjtnbxi.css';
import '../../css/i/i9cg2rj9b.css';
import '../../css/y/ykqnlnbbe.css';
import '../../css/a/a_eltob-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mae_raf5q wm-k"/><path class="jalfqco1n wm-a"/><path class="lmvq19bdy wm-s"/><path class="dlyjtnbxi wm-shadow"/><path class="i9cg2rj9b wm-k"/><path class="wm-a ykqnlnbbe"/><path class="a_eltob-q wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:calendar-search-engrave" /></template>
