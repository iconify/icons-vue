<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulra56alq.css';
import '../../css/w/w03w98eed.css';
import '../../css/z/zx5so0b7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="w03w98eed"/><path class="zx5so0b7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:alex" /></template>
