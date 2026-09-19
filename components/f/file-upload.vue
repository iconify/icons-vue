<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/h463sbbfs.css';
import '../../css/r/rp6fnacut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="h463sbbfs"/><path class="rp6fnacut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:file-upload" /></template>
