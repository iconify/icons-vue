<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lvpwo2bni.css';
import '../../css/s/su8_fik6z.css';
import '../../css/h/hyiuv2blx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lvpwo2bni"/><path class="su8_fik6z"/><path class="hyiuv2blx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:crown-1" /></template>
