<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu98br64n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bu98br64n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-080" /></template>
