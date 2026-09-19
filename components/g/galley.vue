<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy8g0pbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fy8g0pbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:galley" /></template>
