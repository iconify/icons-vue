<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xdza6nhsc.css';
import '../../css/h/h0nqr5iym.css';
import '../../css/d/dwazowq7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xdza6nhsc"/><path class="h0nqr5iym"/><path class="dwazowq7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-beam-sweat-duo" /></template>
