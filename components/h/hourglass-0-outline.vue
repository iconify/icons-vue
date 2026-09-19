<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ow1pw5b1d.css';
import '../../css/z/zb6zeabax.css';
import '../../css/o/o3-x_ssyy.css';
import '../../css/v/vgjyz8brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ow1pw5b1d"/><path clip-rule="evenodd" class="zb6zeabax"/><path class="o3-x_ssyy"/><path clip-rule="evenodd" class="vgjyz8brv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:hourglass-0-outline" /></template>
