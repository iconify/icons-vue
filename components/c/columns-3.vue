<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/i/i9ptl6b7t.css';
import '../../css/t/txd1p9bsj.css';
import '../../css/u/uqgtd6bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="gopnm44um"><rect class="i9ptl6b7t"/><rect class="txd1p9bsj"/><rect class="uqgtd6bue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:columns-3" /></template>
