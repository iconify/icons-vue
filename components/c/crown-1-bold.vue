<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wete5r8ng.css';
import '../../css/b/bvox4ywgs.css';
import '../../css/b/buj03-bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wete5r8ng"/><path class="bvox4ywgs"/><path class="buj03-bwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:crown-1-bold" /></template>
