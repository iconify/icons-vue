<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/te6irpbnf.css';
import '../../css/f/frjjddcio.css';
import '../../css/p/pt6xl9_us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="te6irpbnf"/><path class="frjjddcio"/><path class="pt6xl9_us"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:accessible-duo" /></template>
