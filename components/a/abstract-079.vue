<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npi5k6g5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npi5k6g5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-079" /></template>
