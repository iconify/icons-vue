<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5w009yic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d5w009yic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:gyroscope" /></template>
