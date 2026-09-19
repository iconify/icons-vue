<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs2ej9a6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hs2ej9a6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:leaky-skull" /></template>
