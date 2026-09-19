<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/ldpwkl4dd.css';
import '../../css/f/f8dyh-3bv.css';
import '../../css/g/g2ybw9bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="ldpwkl4dd"/><path clip-rule="evenodd" class="f8dyh-3bv"/><path clip-rule="evenodd" class="g2ybw9bac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:car-bold" /></template>
