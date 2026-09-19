<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocleddcfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="home-outline"><path class="(Stroke) Vector ocleddcfu" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:home-outline" /></template>
