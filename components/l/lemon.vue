<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe1ilz22l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fe1ilz22l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lemon" /></template>
