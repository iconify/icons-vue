<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yd1zh49aw.css';
import '../../css/f/fk3mf7bqi.css';
import '../../css/r/ru_17e40o.css';
import '../../css/c/c04ryybwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="yd1zh49aw"/><path class="fk3mf7bqi"/><path class="ru_17e40o"/><path class="c04ryybwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:arrows-cross" /></template>
