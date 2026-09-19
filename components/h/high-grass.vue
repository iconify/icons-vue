<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7z53u90s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v7z53u90s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:high-grass" /></template>
