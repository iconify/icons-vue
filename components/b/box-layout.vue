<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i_1x96bbx.css';
import '../../css/d/dcq9h0--p.css';
import '../../css/r/rze6_0bfd.css';
import '../../css/e/e2i74rx7p.css';
import '../../css/j/jiv92k4md.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="i_1x96bbx"/><path class="dcq9h0--p"/><rect class="rze6_0bfd"/><rect class="e2i74rx7p"/><path class="jiv92k4md"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:box-layout" /></template>
