<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt1n69bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wt1n69bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-086" /></template>
