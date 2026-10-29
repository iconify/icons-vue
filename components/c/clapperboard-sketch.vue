<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z-5p7fbuo.css';
import '../../css/z/zztk9yikx.css';
import '../../css/c/cclo89b_r.css';
import '../../css/w/wa0mzv3xz.css';
import '../../css/v/vozd3wjqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z-5p7fbuo"/><path class="wm-k zztk9yikx"/><path class="cclo89b_r wm-a"/><path class="wa0mzv3xz wm-k"/><path class="vozd3wjqk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:clapperboard-sketch" /></template>
