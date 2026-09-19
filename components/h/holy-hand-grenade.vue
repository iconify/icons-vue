<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4mz3x9tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w4mz3x9tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:holy-hand-grenade" /></template>
