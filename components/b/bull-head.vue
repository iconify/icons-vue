<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/bw87y6lvh.css';
import '../../css/q/qeljfxiuc.css';
import '../../css/g/g2axgwbig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bw87y6lvh"/><path class="qeljfxiuc"/><path class="g2axgwbig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:bull-head" /></template>
