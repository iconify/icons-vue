<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wga_h3mor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wga_h3mor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-044" /></template>
