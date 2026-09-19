<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/my_15_b2j.css';
import '../../css/b/bdimdovgw.css';
import '../../css/l/lgl2rxbth.css';
import '../../css/y/yazlzye9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="my_15_b2j"/><path class="bdimdovgw"/><path class="lgl2rxbth"/><path class="yazlzye9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:fog" /></template>
