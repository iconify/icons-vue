<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/engh2rwoy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="engh2rwoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-029" /></template>
