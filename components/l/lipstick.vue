<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbt4dkwud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vbt4dkwud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lipstick" /></template>
