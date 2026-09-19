<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/ganijib7d.css';
import '../../css/n/nccjn1-dm.css';
import '../../css/i/ioeyefb3u.css';
import '../../css/h/hx-580b1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><g transform="translate(3 3)"><path class="ganijib7d"/><ellipse class="nccjn1-dm"/><path class="ioeyefb3u"/></g><path class="hx-580b1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:disc" /></template>
