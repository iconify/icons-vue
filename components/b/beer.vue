<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mn56eubrm.css';
import '../../css/c/cnv66pbtf.css';
import '../../css/j/jbq0mbbpz.css';
import '../../css/u/u3u0yrb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mn56eubrm wm-shadow"/><path class="cnv66pbtf wm-shadow"/><path class="jbq0mbbpz"/><path class="u3u0yrb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:beer" /></template>
