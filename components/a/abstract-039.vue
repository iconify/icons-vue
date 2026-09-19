<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wipa-hbze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wipa-hbze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-039" /></template>
