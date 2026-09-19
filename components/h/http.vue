<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp7upebym.css';
import '../../css/r/rirt7bcol.css';
import '../../css/j/jdk23lb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="rirt7bcol"/><path class="jdk23lb_l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:http" /></template>
