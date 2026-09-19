<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d5093jjpo.css';
import '../../css/z/znf5zxa8n.css';
import '../../css/v/vawaipb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d5093jjpo"/><path class="znf5zxa8n"/><path class="vawaipb_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:accessible" /></template>
