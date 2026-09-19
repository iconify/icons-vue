<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jurz1cbnv.css';
import '../../css/o/oeevi_qsd.css';
import '../../css/d/dbinw_m8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="jurz1cbnv"/><path class="oeevi_qsd"/><path class="dbinw_m8x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ellipsis-square-duo" /></template>
