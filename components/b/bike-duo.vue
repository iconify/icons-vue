<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/oy4egu67j.css';
import '../../css/e/ed6fslw1h.css';
import '../../css/w/w7ft8mb7g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="oy4egu67j"/><path class="ed6fslw1h"/><path class="w7ft8mb7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bike-duo" /></template>
