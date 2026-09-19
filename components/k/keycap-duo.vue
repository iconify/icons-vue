<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fuky73q9g.css';
import '../../css/l/lqq65fbvw.css';
import '../../css/z/zur4v2lvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="fuky73q9g"/><path class="lqq65fbvw"/><path class="zur4v2lvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:keycap-duo" /></template>
