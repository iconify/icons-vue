<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b80p1rbvv.css';
import '../../css/m/momohwbsb.css';
import '../../css/q/qr3zbyjzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="b80p1rbvv"/><path class="momohwbsb"/><path class="qr3zbyjzb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:day-duo" /></template>
