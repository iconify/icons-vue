<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rwon19h1w.css';
import '../../css/c/cgl2m5s9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rwon19h1w"/><path vector-effect="non-scaling-stroke" class="cgl2m5s9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:justify-stretch-vertical" /></template>
