<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3vk8wboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n3vk8wboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:glass-ball" /></template>
