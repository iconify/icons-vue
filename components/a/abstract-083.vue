<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrcy5xw5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mrcy5xw5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-083" /></template>
