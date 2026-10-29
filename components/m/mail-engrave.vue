<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vj6r_s8zr.css';
import '../../css/b/b7u2wk65u.css';
import '../../css/a/ai5q-kbba.css';
import '../../css/t/t8-4j7c2p.css';
import '../../css/w/wqb-0n4qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vj6r_s8zr wm-k"/><path class="b7u2wk65u wm-a"/><path class="ai5q-kbba wm-shadow"/><path class="t8-4j7c2p wm-k"/><path class="wm-a wqb-0n4qk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-engrave" /></template>
