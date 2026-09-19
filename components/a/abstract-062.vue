<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-mmbabtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-mmbabtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-062" /></template>
