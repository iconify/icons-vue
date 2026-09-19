<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cy9spm2wh.css';
import '../../css/z/zb6w0600t.css';
import '../../css/h/hb2qjdq3x.css';
import '../../css/u/uy28-vb6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="cy9spm2wh"/><path clip-rule="evenodd" class="zb6w0600t"/><path class="hb2qjdq3x"/><path clip-rule="evenodd" class="uy28-vb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:building-1-outline" /></template>
