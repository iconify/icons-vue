<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk_lp_wlk.css';
import '../../css/a/a3hz4ubdx.css';
import '../../css/t/tsrmwqbrs.css';
import '../../css/p/p9rimibmf.css';
import '../../css/q/qcrhuvb5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGTSxJHbFm" x1="256" x2="256" y1="3" y2="513" gradientTransform="matrix(1 0 0 -1 0 514)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wk_lp_wlk"/><stop offset=".258" class="a3hz4ubdx"/><stop offset=".663" class="tsrmwqbrs"/><stop offset="1"/></linearGradient><path fill="url(#SVGTSxJHbFm)" class="p9rimibmf"/><path class="qcrhuvb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lyrion-music-server" /></template>
