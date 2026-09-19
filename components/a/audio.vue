<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf7p2-bce.css';
import '../../css/i/idjuv0btd.css';
import '../../css/y/y7pnu2bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cf7p2-bce"><path class="idjuv0btd"/><path class="y7pnu2bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:audio" /></template>
