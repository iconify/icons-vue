<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usz420qgc.css';
import '../../css/k/kdeow8k2g.css';
import '../../css/z/zw5w2lbvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="usz420qgc"><path class="kdeow8k2g"/><path class="zw5w2lbvd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:bike-bold" /></template>
