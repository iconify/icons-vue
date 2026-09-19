<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r0nqibciy.css';
import '../../css/x/xqnso42uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="n1lsf0bnc"><path class="r0nqibciy"/><path class="xqnso42uj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:database-remove" /></template>
