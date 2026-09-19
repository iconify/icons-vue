<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1735tben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t1735tben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-113" /></template>
