<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coivkzecr.css';
import '../../css/i/i0zpy4bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="i0zpy4bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-heart-20-bold" /></template>
