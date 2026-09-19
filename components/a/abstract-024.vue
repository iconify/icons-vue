<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf83f3bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mf83f3bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-024" /></template>
