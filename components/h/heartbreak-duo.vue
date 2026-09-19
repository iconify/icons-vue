<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iy-a0yfme.css';
import '../../css/c/ciu_fp-bl.css';
import '../../css/e/em04m3bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="iy-a0yfme"/><path class="ciu_fp-bl"/><path class="em04m3bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heartbreak-duo" /></template>
