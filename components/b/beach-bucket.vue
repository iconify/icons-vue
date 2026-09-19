<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e80v1d7eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e80v1d7eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:beach-bucket" /></template>
