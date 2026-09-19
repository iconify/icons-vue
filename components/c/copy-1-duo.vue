<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xu2hubcwa.css';
import '../../css/f/fc-f16bov.css';
import '../../css/u/u_2b3msej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xu2hubcwa"/><path class="fc-f16bov"/><path class="u_2b3msej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:copy-1-duo" /></template>
