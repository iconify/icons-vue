<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/b/bmws_1bba.css';
import '../../css/b/bc020x-_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="gopnm44um"><rect class="bmws_1bba"/><rect class="bc020x-_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:columns-2" /></template>
