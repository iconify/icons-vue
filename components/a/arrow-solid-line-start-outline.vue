<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rftmwyb_p.css';
import '../../css/b/bwcarn5wh.css';
import '../../css/m/mz5y2hvkq.css';
import '../../css/t/t8ue8_09r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rftmwyb_p"/><path class="bwcarn5wh"/><path clip-rule="evenodd" class="mz5y2hvkq"/><path class="t8ue8_09r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-line-start-outline" /></template>
