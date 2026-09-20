<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpsiiab0r.css';
import '../../css/i/ivcy6gb4b.css';
import '../../css/j/jxkh7fuzr.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/k/kltkxu7pk.css';
import '../../css/f/fnabs1bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="dpsiiab0r"><path class="ivcy6gb4b"/><path class="jxkh7fuzr"/></g><g class="ij2x_72vy"><path class="kltkxu7pk"/><path class="fnabs1bao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bat" /></template>
