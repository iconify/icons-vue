<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zn0dbsspf.css';
import '../../css/h/hdkg49b6e.css';
import '../../css/z/znts8wbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="zn0dbsspf"/><path class="hdkg49b6e"/><path class="znts8wbcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:dropbox" /></template>
