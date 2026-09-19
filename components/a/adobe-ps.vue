<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp7upebym.css';
import '../../css/g/gr7r812zo.css';
import '../../css/s/s0zq9lpyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="xp7upebym"><path class="gr7r812zo"/><path class="s0zq9lpyr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:adobe-ps" /></template>
