<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw6l5vb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hw6l5vb8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-040" /></template>
