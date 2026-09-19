<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncvg5reyd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ncvg5reyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-107" /></template>
