<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mihin5bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mihin5bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:droplets" /></template>
