<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ou2mbsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d_ou2mbsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-092" /></template>
