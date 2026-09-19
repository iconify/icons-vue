<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erx8w3len.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="bolt-outline"><path class="(Stroke) 85 Vector erx8w3len" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:bolt-outline" /></template>
