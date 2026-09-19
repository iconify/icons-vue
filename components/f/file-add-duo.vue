<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zl1xbraru.css';
import '../../css/n/n5yhx2bkg.css';
import '../../css/q/qwd394bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zl1xbraru"/><path class="n5yhx2bkg"/><path class="qwd394bsp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:file-add-duo" /></template>
