<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a__s2g6zp.css';
import '../../css/x/xo73r-1bv.css';
import '../../css/i/isuy6sbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="xo73r-1bv"/><path class="isuy6sbwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chevron-double-bold" /></template>
