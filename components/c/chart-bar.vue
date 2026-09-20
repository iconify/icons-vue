<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt-pin3gu.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p_3zmsvya.css';
import '../../css/b/bw2p-ubhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGvfUnedaT" class="mt-pin3gu"/></defs><g class="ft5dv1b6b"><use href="#SVGvfUnedaT"/><use href="#SVGvfUnedaT" class="p_3zmsvya"/><path class="bw2p-ubhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chart-bar" /></template>
