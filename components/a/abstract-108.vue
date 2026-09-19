<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao0ucxbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ao0ucxbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-108" /></template>
