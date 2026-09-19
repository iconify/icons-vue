<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d_q9h-uxq.css';
import '../../css/g/gi9kwacwi.css';
import '../../css/g/ggqrbdggc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="d_q9h-uxq"/><path class="gi9kwacwi"/><path class="ggqrbdggc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:canoe-2-duo" /></template>
