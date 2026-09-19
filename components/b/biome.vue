<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qa-0ch2ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qa-0ch2ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:biome" /></template>
