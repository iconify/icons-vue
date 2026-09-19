<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqaaf-3rv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vqaaf-3rv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:goal-keeper" /></template>
