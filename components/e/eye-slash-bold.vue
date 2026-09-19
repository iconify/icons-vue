<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nlbukzbvh.css';
import '../../css/n/nsvaqzcrz.css';
import '../../css/e/enxj31s0p.css';
import '../../css/b/bgasabkle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="nlbukzbvh"/><path class="nsvaqzcrz"/><path class="enxj31s0p"/><path clip-rule="evenodd" class="bgasabkle"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-slash-bold" /></template>
