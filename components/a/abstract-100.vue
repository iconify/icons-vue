<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k10q4pbry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k10q4pbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-100" /></template>
