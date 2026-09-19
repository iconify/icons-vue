<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rmp5hgbqp.css';
import '../../css/d/dfbuaacdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g transform="translate(4)" class="n1lsf0bnc"><ellipse class="rmp5hgbqp"/><path class="dfbuaacdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:ipod" /></template>
