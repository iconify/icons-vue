<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt7go7wxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pt7go7wxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:health-increase" /></template>
