<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ulvreypdp.css';
import '../../css/d/d_6nk9tcq.css';
import '../../css/s/sy_7xmbwa.css';
import '../../css/n/n1-j0_bve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ulvreypdp"/><path clip-rule="evenodd" class="d_6nk9tcq"/><path clip-rule="evenodd" class="sy_7xmbwa"/><path class="n1-j0_bve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:chart-bar-1" /></template>
