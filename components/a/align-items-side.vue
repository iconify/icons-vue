<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rohgp77ig.css';
import '../../css/w/wgt29qa_p.css';
import '../../css/s/smg7inkbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rohgp77ig"/><path class="wgt29qa_p"/><path class="smg7inkbg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:align-items-side" /></template>
