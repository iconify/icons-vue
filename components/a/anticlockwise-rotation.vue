<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccr8qtrht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ccr8qtrht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:anticlockwise-rotation" /></template>
