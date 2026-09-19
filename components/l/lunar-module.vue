<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whfw6qb_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whfw6qb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:lunar-module" /></template>
