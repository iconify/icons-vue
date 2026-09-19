<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccrh14qgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccrh14qgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-096" /></template>
