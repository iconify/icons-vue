<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmpzvobal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jmpzvobal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-027" /></template>
