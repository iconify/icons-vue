<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnt4rgbuc.css';
import '../../css/x/x1mdp195q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="xnt4rgbuc"/><path class="x1mdp195q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:brown-hexagon" /></template>
