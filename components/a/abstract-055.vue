<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuy1p_-se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xuy1p_-se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-055" /></template>
