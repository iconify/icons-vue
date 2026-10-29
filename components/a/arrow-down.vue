<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cnox2_2_k.css';
import '../../css/k/kur13mblj.css';
import '../../css/d/dr_d4wbmt.css';
import '../../css/a/aq9b667ef.css';
import '../../css/i/i8udtsb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cnox2_2_k wm-deco"/><path class="kur13mblj wm-k"/><path class="dr_d4wbmt wm-k"/><path class="aq9b667ef wm-k"/><path class="i8udtsb8f wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:arrow-down" /></template>
