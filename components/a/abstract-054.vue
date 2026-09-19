<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7uw6-bjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c7uw6-bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-054" /></template>
