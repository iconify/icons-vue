<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqhdsrbpo.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/b/b2tl1fbgr.css';
import '../../css/o/oi3x71bay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fqhdsrbpo"/><g class="ij2x_72vy"><path class="b2tl1fbgr"/><path class="oi3x71bay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:archive" /></template>
