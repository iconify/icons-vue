<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qzf3b8vsm.css';
import '../../css/v/vp63-wbkq.css';
import '../../css/s/se5x8jbpl.css';
import '../../css/v/vgawabc-n.css';
import '../../css/u/uhe1tj0vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qzf3b8vsm"/><path class="vp63-wbkq wm-k"/><path class="se5x8jbpl wm-a"/><path class="vgawabc-n wm-k"/><path class="uhe1tj0vi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-check-big-sketch" /></template>
