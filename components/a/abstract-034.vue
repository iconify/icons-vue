<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgw9obqmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pgw9obqmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-034" /></template>
