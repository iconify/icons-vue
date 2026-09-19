<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/we5eze0cw.css';
import '../../css/q/qmnaebbzc.css';
import '../../css/i/icj2onb3b.css';
import '../../css/y/y7u-8kb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="we5eze0cw"/><path class="qmnaebbzc"/><path class="icj2onb3b"/><path class="y7u-8kb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:farm" /></template>
