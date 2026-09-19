<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qmu0cybng.css';
import '../../css/d/dvvbd46va.css';
import '../../css/v/vdk6b1irq.css';
import '../../css/d/dhvygdbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="qmu0cybng"/><path class="dvvbd46va"/><path class="vdk6b1irq"/><path class="dhvygdbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:boombox" /></template>
