<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmj_40xrr.css';
import '../../css/f/fu_yyil7h.css';
import '../../css/e/e8ed0bc7f.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/w/wje_roblw.css';
import '../../css/u/uxx5stghf.css';
import '../../css/b/bs2p_wqwk.css';
import '../../css/n/nqy3w-3ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="qmj_40xrr"/><path class="fu_yyil7h"/><path class="e8ed0bc7f"/><g class="jn8qy4bru"><path class="wje_roblw"/><path class="uxx5stghf"/><path class="bs2p_wqwk"/><path class="nqy3w-3ne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:goat" /></template>
