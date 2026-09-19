<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ck1931bjh.css';
import '../../css/q/qfd3apbyf.css';
import '../../css/d/det13e0ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ck1931bjh"/><path class="qfd3apbyf"/><path class="det13e0ij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:heart-half-1" /></template>
