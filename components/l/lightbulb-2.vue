<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f3wxftbjs.css';
import '../../css/i/ipu91p9hu.css';
import '../../css/d/d-6krk_4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f3wxftbjs"/><path clip-rule="evenodd" class="ipu91p9hu"/><path class="d-6krk_4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:lightbulb-2" /></template>
