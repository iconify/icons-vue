<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/ntluoabif.css';
import '../../css/l/l4rtpqumh.css';
import '../../css/u/u5184whll.css';
import '../../css/y/y6sbpzbuu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ntluoabif"/><path class="l4rtpqumh wm-k"/><path class="u5184whll wm-k"/><path class="wm-a y6sbpzbuu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-sketch" /></template>
