<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t95d3yb2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t95d3yb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-115" /></template>
