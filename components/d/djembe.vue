<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4y6-0tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yt4y6-0tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:djembe" /></template>
