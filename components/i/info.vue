<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/v/vo03lkbbh.css';
import '../../css/j/jbw52u0nv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><ellipse class="vo03lkbbh"/><path class="jbw52u0nv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:info" /></template>
