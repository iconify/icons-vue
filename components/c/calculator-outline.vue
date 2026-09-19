<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f2j1lr8fy.css';
import '../../css/k/kb76wyfeg.css';
import '../../css/k/kwz1j7bdg.css';
import '../../css/t/txgz9c5yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f2j1lr8fy"/><path clip-rule="evenodd" class="kb76wyfeg"/><path class="kwz1j7bdg"/><path clip-rule="evenodd" class="txgz9c5yh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:calculator-outline" /></template>
