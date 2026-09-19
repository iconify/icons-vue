<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3pmyqbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p3pmyqbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fishing-pole" /></template>
