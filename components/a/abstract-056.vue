<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw684x6og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kw684x6og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-056" /></template>
