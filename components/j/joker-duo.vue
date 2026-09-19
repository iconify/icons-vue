<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i7z2n2wtr.css';
import '../../css/d/dznf5ccgt.css';
import '../../css/x/xerbc4b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i7z2n2wtr"/><path class="dznf5ccgt"/><path class="xerbc4b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:joker-duo" /></template>
