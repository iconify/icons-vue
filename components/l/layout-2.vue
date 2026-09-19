<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fir3l4bbe.css';
import '../../css/f/ftm8sv4vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="fir3l4bbe"/><path class="ftm8sv4vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:layout-2" /></template>
