<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo9ej9zfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jo9ej9zfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-crossover-left" /></template>
