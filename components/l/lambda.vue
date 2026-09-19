<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsjvjf5_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hsjvjf5_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lambda" /></template>
