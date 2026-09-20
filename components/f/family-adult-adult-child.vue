<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uncoc-6_u.css';
import '../../css/d/d4vglyb4j.css';
import '../../css/h/hnmhb87hw.css';
import '../../css/v/vmo56tb0e.css';
import '../../css/i/iiutvsm2y.css';
import '../../css/j/j84e5gbhw.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/c/ccwn74xda.css';
import '../../css/w/wdmdue19i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="uncoc-6_u"><path class="d4vglyb4j"/><circle class="hnmhb87hw"/><circle class="vmo56tb0e"/><circle class="iiutvsm2y"/><path class="j84e5gbhw"/></g><g class="jn8qy4bru"><circle class="iiutvsm2y"/><circle class="hnmhb87hw"/><path class="ccwn74xda"/><circle class="vmo56tb0e"/><path class="wdmdue19i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:family-adult-adult-child" /></template>
