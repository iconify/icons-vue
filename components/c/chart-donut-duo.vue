<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v6ldc6i3j.css';
import '../../css/e/eb5uhxb5u.css';
import '../../css/o/orpyotf8m.css';
import '../../css/m/m-alvoznk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="v6ldc6i3j"/><path class="eb5uhxb5u"/><path class="orpyotf8m"/><path class="m-alvoznk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:chart-donut-duo" /></template>
