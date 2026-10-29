<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lh23q0bub.css';
import '../../css/f/fihxnqbec.css';
import '../../css/q/qy154lb5h.css';
import '../../css/s/sil1qubyf.css';
import '../../css/k/ks2n1wboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lh23q0bub"/><path class="fihxnqbec wm-k"/><path class="qy154lb5h wm-a"/><path class="sil1qubyf wm-k"/><path class="ks2n1wboh wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:butterfly-sketch" /></template>
