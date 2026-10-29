<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i6fb6s0-v.css';
import '../../css/s/slkbs6l7f.css';
import '../../css/p/pj62yub9y.css';
import '../../css/a/a39eozb4h.css';
import '../../css/o/oj34xxbcj.css';
import '../../css/k/k5-wqgb-q.css';
import '../../css/d/diyvfeblp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i6fb6s0-v wm-k"/><path class="slkbs6l7f wm-a"/><path class="pj62yub9y wm-shadow"/><path class="a39eozb4h wm-k"/><path class="oj34xxbcj wm-k"/><path class="k5-wqgb-q wm-k"/><path class="diyvfeblp wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:handshake-engrave" /></template>
