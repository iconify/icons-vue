<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyt-gdcty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wyt-gdcty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dripping-knife" /></template>
