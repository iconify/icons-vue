<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsws4ub3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsws4ub3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:flame-spin" /></template>
