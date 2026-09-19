<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2ilai0fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q2ilai0fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:icicles-aura" /></template>
