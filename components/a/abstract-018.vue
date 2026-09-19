<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y21a7pbln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y21a7pbln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-018" /></template>
