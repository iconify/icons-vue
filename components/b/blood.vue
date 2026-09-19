<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aj9x6h2zo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aj9x6h2zo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:blood" /></template>
