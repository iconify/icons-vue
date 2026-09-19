<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rr4lywbge.css';
import '../../css/l/lrw14ub0z.css';
import '../../css/g/gytayk9aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rr4lywbge"/><path class="lrw14ub0z"/><path class="gytayk9aj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:grin-tears-duo" /></template>
