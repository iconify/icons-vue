<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8_kczbsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s8_kczbsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:burning-forest" /></template>
