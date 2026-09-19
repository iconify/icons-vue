<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjuu2tb9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gjuu2tb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bonsai-tree" /></template>
