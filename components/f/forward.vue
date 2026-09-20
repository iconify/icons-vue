<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij2x_72vy.css';
import '../../css/i/ilr6hpbnj.css';
import '../../css/p/pcurjzbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="ilr6hpbnj"/><path class="pcurjzbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:forward" /></template>
