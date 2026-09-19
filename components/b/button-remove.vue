<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/q/qzhlbtb8j.css';
import '../../css/c/cpwgzvbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="qzhlbtb8j"/><path class="cpwgzvbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:button-remove" /></template>
