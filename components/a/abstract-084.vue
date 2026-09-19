<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz37dabew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yz37dabew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-084" /></template>
