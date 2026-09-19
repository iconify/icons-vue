<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsb-o9f4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsb-o9f4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-001" /></template>
