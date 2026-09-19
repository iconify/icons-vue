<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rz42u830k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rz42u830k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-097" /></template>
