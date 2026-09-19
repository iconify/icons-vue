<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_daflb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l_daflb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-013" /></template>
