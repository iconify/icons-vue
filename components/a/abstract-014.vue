<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8kd2vbis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m8kd2vbis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-014" /></template>
