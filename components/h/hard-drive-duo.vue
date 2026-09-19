<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q5eb5rb5w.css';
import '../../css/k/kkocbubzf.css';
import '../../css/c/ctpho9xop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="q5eb5rb5w"/><path class="kkocbubzf"/><path class="ctpho9xop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hard-drive-duo" /></template>
