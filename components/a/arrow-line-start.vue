<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wkp8a0bcv.css';
import '../../css/y/y000a8cns.css';
import '../../css/o/os0hnf_5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="wkp8a0bcv"/><path class="y000a8cns"/><path class="os0hnf_5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:arrow-line-start" /></template>
