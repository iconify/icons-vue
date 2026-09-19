<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i03jw6b9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i03jw6b9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-090" /></template>
