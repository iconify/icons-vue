<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulra56alq.css';
import '../../css/w/w03w98eed.css';
import '../../css/v/v5k322mny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="w03w98eed"/><path class="v5k322mny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:heroku" /></template>
