<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yi0vp2biw.css';
import '../../css/p/plq8cklzl.css';
import '../../css/n/nqeg6l1lc.css';
import '../../css/n/ns361sykx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yi0vp2biw"/><path class="plq8cklzl"/><path clip-rule="evenodd" class="nqeg6l1lc"/><path class="ns361sykx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:brain-bold" /></template>
