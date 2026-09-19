<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvzo8oh1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="grid-outline"><path class="Vector uvzo8oh1p" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:grid-outline" /></template>
