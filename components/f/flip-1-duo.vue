<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j7if260ae.css';
import '../../css/x/xox5c7kpu.css';
import '../../css/k/kij8agj6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="j7if260ae"/><path class="xox5c7kpu"/><path class="kij8agj6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:flip-1-duo" /></template>
