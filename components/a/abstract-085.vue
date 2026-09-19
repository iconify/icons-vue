<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnolv9s0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dnolv9s0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-085" /></template>
