<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mac0w8brc.css';
import '../../css/i/i0l9gyb3p.css';
import '../../css/z/zrlh-6b7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mac0w8brc"/><path class="i0l9gyb3p"/><path class="zrlh-6b7n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:atom" /></template>
