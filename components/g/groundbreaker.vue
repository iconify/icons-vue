<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpn07kbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fpn07kbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:groundbreaker" /></template>
