<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o5mqf-brr.css';
import '../../css/b/bb2k93bxr.css';
import '../../css/e/ey2r4hb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="o5mqf-brr"/><path class="bb2k93bxr"/><path class="ey2r4hb-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bezier-triangle-duo" /></template>
