<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgsnhr3ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kgsnhr3ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magick-trick" /></template>
