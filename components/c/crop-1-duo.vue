<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/ea_n0eb7u.css';
import '../../css/l/lwi-ajbjg.css';
import '../../css/d/do6sbpbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ea_n0eb7u"/><path class="lwi-ajbjg"/><path class="do6sbpbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crop-1-duo" /></template>
