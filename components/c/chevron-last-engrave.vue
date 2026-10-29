<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sci640bhs.css';
import '../../css/b/bj-rp9qcq.css';
import '../../css/t/tv7ggr2_t.css';
import '../../css/a/azxfktbgs.css';
import '../../css/z/zhjtmfbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sci640bhs wm-k"/><path class="bj-rp9qcq wm-a"/><path class="tv7ggr2_t wm-shadow"/><path class="azxfktbgs wm-k"/><path class="wm-a zhjtmfbrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevron-last-engrave" /></template>
