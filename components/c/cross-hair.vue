<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/b/bl_1urbwu.css';
import '../../css/h/h5-7nhb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="bl_1urbwu"/><path class="h5-7nhb8d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:cross-hair" /></template>
