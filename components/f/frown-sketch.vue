<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/os-fgmamw.css';
import '../../css/i/in0agd6nm.css';
import '../../css/f/fzaba2bnm.css';
import '../../css/a/af1lg4blq.css';
import '../../css/s/sbnuhvbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="os-fgmamw"/><path class="in0agd6nm wm-k"/><path class="fzaba2bnm wm-a"/><path class="af1lg4blq wm-k"/><path class="sbnuhvbhi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:frown-sketch" /></template>
