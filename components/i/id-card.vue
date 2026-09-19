<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di5vm559l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="di5vm559l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:id-card" /></template>
