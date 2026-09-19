<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s53vmbcgz.css';
import '../../css/s/ss6--sbpb.css';
import '../../css/d/d_hbrvb-g.css';
import '../../css/f/fazon-bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="s53vmbcgz"><path class="ss6--sbpb"/><path class="d_hbrvb-g"/><path class="fazon-bzg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:luau-check" /></template>
