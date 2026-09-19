<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xh9z62bhv.css';
import '../../css/n/n0qaccbrc.css';
import '../../css/d/dfsxo8ehe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xh9z62bhv"/><path class="n0qaccbrc"/><path class="dfsxo8ehe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-duo" /></template>
