<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaf72r2iq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="filter-outline"><path class="(Stroke) 38 Vector vaf72r2iq" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:filter-outline" /></template>
