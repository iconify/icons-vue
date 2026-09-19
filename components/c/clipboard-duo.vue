<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cdmgm25pw.css';
import '../../css/z/z7cyubboc.css';
import '../../css/p/po49iib2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="cdmgm25pw"/><path class="z7cyubboc"/><path class="po49iib2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:clipboard-duo" /></template>
