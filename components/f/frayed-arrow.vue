<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn_elfbym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mn_elfbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:frayed-arrow" /></template>
