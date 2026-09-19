<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efm3k2f6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="efm3k2f6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-058" /></template>
