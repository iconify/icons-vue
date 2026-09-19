<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/isrh1wb3s.css';
import '../../css/z/zi4o31-hv.css';
import '../../css/k/klh9tdqcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="isrh1wb3s"/><path clip-rule="evenodd" class="zi4o31-hv"/><path clip-rule="evenodd" class="klh9tdqcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:folder-open-1" /></template>
