<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/ciqngbc0l.css';
import '../../css/j/j9vih8dli.css';
import '../../css/w/w9-6243pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="ciqngbc0l"/><path class="j9vih8dli"/><path class="w9-6243pt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:chart-line" /></template>
