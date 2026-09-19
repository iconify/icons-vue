<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_2b6abro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x_2b6abro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-038" /></template>
