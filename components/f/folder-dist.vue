<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_2lkqbxb.css';
import '../../css/h/hfb1keruk.css';
import '../../css/r/rp93njbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="t_2lkqbxb"><path class="hfb1keruk"/><path class="rp93njbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-dist" /></template>
