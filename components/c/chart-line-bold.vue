<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/juq13gbkq.css';
import '../../css/h/hijqlccze.css';
import '../../css/u/uhfj7cbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="juq13gbkq"/><path class="hijqlccze"/><path class="uhfj7cbdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-line-bold" /></template>
