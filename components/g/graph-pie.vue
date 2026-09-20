<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t6y5t4bua.css';
import '../../css/k/k2vx3qbnw.css';
import '../../css/u/u16kknbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="ft5dv1b6b"><path class="t6y5t4bua"/><path class="k2vx3qbnw"/><path class="u16kknbeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-stickies-color:graph-pie" /></template>
