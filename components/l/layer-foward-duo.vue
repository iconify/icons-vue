<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/imc-y6tvu.css';
import '../../css/q/qv6egzw5f.css';
import '../../css/f/friwwhbgo.css';
import '../../css/k/krqewebem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="imc-y6tvu"/><path class="qv6egzw5f"/><path class="friwwhbgo"/><path class="krqewebem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:layer-foward-duo" /></template>
