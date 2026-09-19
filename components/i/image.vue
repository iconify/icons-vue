<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/y49vkvlfv.css';
import '../../css/e/elzzhttxr.css';
import '../../css/c/ciumniaxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><rect class="y49vkvlfv"/><path clip-rule="evenodd" class="elzzhttxr"/><path class="ciumniaxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:image" /></template>
