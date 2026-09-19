<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j6hqicceo.css';
import '../../css/m/mryf-abgs.css';
import '../../css/t/tseibwsee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j6hqicceo"/><path class="mryf-abgs"/><path class="tseibwsee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:flip-1" /></template>
